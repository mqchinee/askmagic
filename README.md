# AskMagic `1.0.0`

[PyPI](https://pypi.org/project/askmagic/)

```python
pip install askmagic
```

## Examples

```python
import askmagic

print(askmagic.ask.question("en", "Object Pascal sucks?"))

print("\n")

print(askmagic.ask.answer("en"))
print(askmagic.ask.answer("uk"))
print(askmagic.ask.answer("ru"))
```

### Output

```
Magic ball
Your question: Object Pascal sucks?

My answer:
Try again! ❓

My opinion is yes! ✅
Моя відповідь ні. 🚫
Не могу сейчас предсказать.. ❓
```


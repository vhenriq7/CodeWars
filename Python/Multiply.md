# Multiply

**Plataforma:** [Codewars](https://www.codewars.com/kata/50654ddff44f800200000004)  
**Dificuldade:** 8 kyu  
**Tags:** Debugging, Fundamentals

## Desafio

This code does not execute properly. Try to figure out why.

## Código original

```python
def multiply(a, b):
    a * b
```

## Solução — Python

```python
def multiply(a, b):
    res = a * b
    return res
```

**Erro corrigido:** a função original calculava `a * b`, mas não retornava o resultado.

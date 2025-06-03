
# Environment Setup
```python
conda create -n modelscope python==3.10 -y
conda activate modelscope
pip install uv
uv pip install -e .
```

result.jsonl --> toolcall.jsonl --> result.json
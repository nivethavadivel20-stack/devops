steps:
  - uses: actions/checkout@v4

  - uses: actions/setup-python@v4
    with:
      python-version: '3.13'

  - name: Run Python Script
    run: python my_script.py

# eed_uv_sample_project

question - why can't i import the package?

```bash
$ uv venv .venv
Using CPython 3.13.2
Creating virtual environment at: .venv
Activate with: source .venv/Scripts/activate

$ uv pip install -e .
Resolved 1 package in 5ms
      Built eed-uv-sample-project @ file:///C:/dev/github/EED85/eed_uv_sample_project
Prepared 1 package in 2.74s
Installed 1 package in 7ms
 + eed-uv-sample-project==0.1.0 (from file:///C:/dev/github/EED85/eed_uv_sample_project)

$ uv pip show eed-uv-sample-project
Name: eed-uv-sample-project
Version: 0.1.0
Location: C:\dev\github\EED85\eed_uv_sample_project\.venv\Lib\site-packages
Editable project location: C:\dev\github\EED85\eed_uv_sample_project
Requires:
Required-by:

$ C:/dev/github/EED85/eed_uv_sample_project/.venv/Scripts/python.exe c:/dev/github/EED85/eed_uv_sample_project/main.py
Traceback (most recent call last):
  File "c:\dev\github\EED85\eed_uv_sample_project\main.py", line 1, in <module>
    import eed_uv_sample_project
ModuleNotFoundError: No module named 'eed_uv_sample_project'
(.venv)
```

# eed_uv_sample_project

question - why can't i import the package?

```bash
$ uv venv .venv
Using CPython 3.13.2
Creating virtual environment at: .venv
Activate with: source .venv/Scripts/activate

$ uv pip install e .
Resolved 2 packages in 216ms
      Built eed-uv-sample-project @ file:///C:/dev/github/EED85/eed_uv_sample_project
Prepared 1 package in 3.72s
Installed 2 packages in 7ms
 + e==1.4.5
 + eed-uv-sample-project==0.1.0 (from file:///C:/dev/github/EED85/eed_uv_sample_project)

$ uv pip show eed-uv-sample-project
Name: eed-uv-sample-project
Version: 0.1.0
Location: C:\dev\github\EED85\eed_uv_sample_project\.venv\Lib\site-packages
Requires:
Required-by:

$ C:/dev/github/EED85/eed_uv_sample_project/.venv/Scripts/python.exe c:/dev/github/EED85/eed_uv_sample_project/main.py
Traceback (most recent call last):
  File "c:\dev\github\EED85\eed_uv_sample_project\main.py", line 1, in <module>
    import eed_uv_sample_project
ModuleNotFoundError: No module named 'eed_uv_sample_project'
(.venv)
```

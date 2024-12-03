## Opening JupyterLab Remotely

To access Jupyter Lab on a remote server, follow these steps after logging in:

1. Enter the following command in your terminal:

    ```
    path/to/the/jupyter-lab/jupyter-lab password
    ```

2. Start Jupyter Lab with the following command:

    ```
    path/to/the/jupyter-lab/jupyter-lab --ip='*' --no-browser
    ```

    If the IP address of the remote server is `10.10.10.10` and the notebook launches on port `8889`, open a browser on your local machine and type the following URL:

    ```
    http://10.10.10.10:8889
    ```

    Make sure to replace `10.10.10.10` with the actual IP address of your remote server and `8889` with the port number specified during notebook launch.

Copy and paste the commands directly into your terminal to access JupyterLab remotely.

### For Jupyter notebook use the same procedure, instead of lab use notebook

# Implementation of the Paper ["A Single Backlit Image Enhancement Method For Improvement Of Visibility Of Dark Part"](https://ieeexplore.ieee.org/document/9506526) by M. Akai _et al._

_Refer to the following [paper](https://ieeexplore.ieee.org/document/9506526) for mathematical modeling, experimentation and comparisons with other models._

## Quick Start
- Install the requirements using the following command:
    ```console
    $ pip install -r requirements.txt
    ```
- Follow the notebook to get results. Modify the `parameters` dictionary to load up other images.
    ```python
    parameters = {
        "FIGURE": "<Image file, eg: fig1.png>",
        "GAMMA": 2,
        "ALPHA": 0.7,
        "EPSILON": 1e-7
    }
    ```

## Results
- Processed and original image. `(fig1.png)`
    ![fig1_proc.png](./Images/fig1_proc.png)
    ![fig1.png](./Images/fig1.png)
- Processed and original image. `(fig2.jpg)`
    ![fig2_proc.png](./Images/fig2_proc.png)
    ![fig2.png](./Images/fig2.jpg)
- Processed and original image. `(fig3.png)`
    ![fig3_proc.png](./Images/fig3_proc.png)
    ![fig3.png](./Images/fig3.png)
- Processed and original image. `(fig4.jpg)`
    ![fig4_proc.png](./Images/fig4_proc.png)
    ![fig4.png](./Images/fig4.png)
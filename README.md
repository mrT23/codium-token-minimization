# CodiumAI token minimization

In this repository we provide implementation for minimizing the number of LLM code tokens of a Python code.
The code is based on the [blog post](https://github.com/Alibaba-MIIL/ASL/blob/main/tests/test_asl.py)

An example code for token minimization is provided in the `example.py` file.

<p align="center">
 <table class="tg">
 <tr>
    <td class="tg-c3ow" style="background-color: white;"><h5>Tokens for baseline code</h5><img alt="Baseline Tokens" src=pics/baseline_tokens.png align="center" width="400"  style="background-color: white;"></td>
  </tr>
  <tr>
    <td class="tg-c3ow" style="background-color: white;"><h5>Tokens for tabified code</h5><img alt="Tabified Tokens" src=pics/tabified_tokens.png align="center" width="400"  style="background-color: white;"></td>
  </tr>
  <tr>
    <td class="tg-c3ow" style="background-color: white;"><h5>Tokens for tabified and minimized code</h5><img alt="Tabified and minimized code tokens" src=pics/tabified_and_minimized_tokens.png align="center" width="400"  style="background-color: white;"></td>
  </tr>
</table>
</p>

Note that both tabification and minimization operations do not change the code functionality.

## Acknowledgement
To perform code minimization, we use the excellent [Python Minifier](https://github.com/dflook/python-minifier) package.
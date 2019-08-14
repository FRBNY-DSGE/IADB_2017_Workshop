# Macroeconomic Modeling with Julia

Code and teaching material for "Macroeconomic Modeling with Julia", a workshop given for the IADB at the Central Bank of Argentina in December 2017.

## Tentative Outline

- December 18, 2:00 - 2:30 pm: Introduction to Julia
- December 18, 2:45 - 3:45 pm: Syntax
- December 18, 4:00 - 5:30 pm: Types and multiple dispatch
- December 19, 9:00 - 9:30 am: Package ecosystem
- December 19, 9:45 - 11:00 am: State-space models and DSGE.jl

## Software

We assume that participants will have access to

* [Julia v0.6.1](https://julialang.org/downloads/)
* [IJulia](https://github.com/JuliaLang/IJulia.jl) and [Jupyter notebooks](https://jupyter.org/): type `Pkg.add("IJulia")` in the Julia REPL
  - Optional: [RISE](https://github.com/damianavila/RISE), a Jupyter extension which lets you convert notebooks (which are already in slide format) to slides within the browser and run code blocks in the slides. After installing IJulia, run in the Julia REPL:
    ```julia
    using Conda
    Conda.add_channel("damianavila82")
    Conda.add("rise")
    ```
* [DSGE](https://github.com/FRBNY-DSGE/DSGE.jl): type `Pkg.add("DSGE")` in the Julia REPL

## Resources

* [Cheat sheets](http://cheatsheets.quantecon.org/) for MATLAB and Python users
* [Lectures](http://lectures.quantecon.org/) for learning Julia, or for economics concepts
* [Discourse forum](http://discourse.julialang.org/) for Julia questions

## Contact

* Abhi Gupta: abhi.gupta@ny.frb.org
* Pearl Li: pearl.li@ny.frb.org

Disclaimer
------
Copyright Federal Reserve Bank of New York. You may reproduce, use, modify, make derivative works of, and distribute and this code in whole or in part so long as you keep this notice in the documentation associated with any distributed works. Neither the name of the Federal Reserve Bank of New York (FRBNY) nor the names of any of the authors may be used to endorse or promote works derived from this code without prior written permission. Portions of the code attributed to third parties are subject to applicable third party licenses and rights. By your use of this code you accept this license and any applicable third party license.

THIS CODE IS PROVIDED ON AN "AS IS" BASIS, WITHOUT ANY WARRANTIES OR CONDITIONS OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OR CONDITIONS OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE, EXCEPT TO THE EXTENT THAT THESE DISCLAIMERS ARE HELD TO BE LEGALLY INVALID. FRBNY IS NOT, UNDER ANY CIRCUMSTANCES, LIABLE TO YOU FOR DAMAGES OF ANY KIND ARISING OUT OF OR IN CONNECTION WITH USE OF OR INABILITY TO USE THE CODE, INCLUDING, BUT NOT LIMITED TO DIRECT, INDIRECT, INCIDENTAL, CONSEQUENTIAL, PUNITIVE, SPECIAL OR EXEMPLARY DAMAGES, WHETHER BASED ON BREACH OF CONTRACT, BREACH OF WARRANTY, TORT OR OTHER LEGAL OR EQUITABLE THEORY, EVEN IF FRBNY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES OR LOSS AND REGARDLESS OF WHETHER SUCH DAMAGES OR LOSS IS FORESEEABLE.

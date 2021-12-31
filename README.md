# <p align=center>`Awesome Light Transport`</p>
A collection of resources on light transport, mainly focus on codes (official or reproduce)

## 2021

### SIGGRAPH

**A Generic Framework for Physical Light Transport** <br>
*[Shlomi Steinberg](https://ssteinberg.xyz/), [Lingqi Yan](https://sites.cs.ucsb.edu/~lingqi/)* <br>
SIGGRAPH 2021. [[Project Website](https://ssteinberg.xyz/2021/04/26/generic_physical_light_transport_framework/)] [[Paper](https://ssteinberg.xyz/202104_generic_physical_light_transport_framework_paper.pdf)] [[Official Code](https://ssteinberg.xyz/202104_generic_physical_light_transport_framework_mitsuba_src_code.7z)]

**BRDF Importance Sampling for Polygonal Lights** <br>
*[Christoph Peters](https://momentsingraphics.de/)* <br>
SIGGRAPH 2021. [[Project Website](https://momentsingraphics.de/Siggraph2021.html)] [[Paper](https://momentsingraphics.de/Media/Siggraph2021/peters2021-brdf_importance_sampling_for_polygonal_lights-paper.pdf)] [[Official Code](https://github.com/MomentsInGraphics/vulkan_renderer)]

**A Non-Exponential Transmittance Model for Volumetric Scene Representations** <br>
*Delio Vicini, Wenzel Jakob, Anton Kaplanyan* <br>
SIGGRAPH 2021. [[Project Website](http://rgl.epfl.ch/publications/Vicini2021NonExponential)] [[Paper](http://rgl.s3.eu-central-1.amazonaws.com/media/papers/Vicini2021NonExponential.pdf)] [[Official Code](https://github.com/dvicini/non-exp-transmittance-torch)]

**Primary-Space Adaptive Control Variates using Piecewise-Polynomial Approximations** <br>
*Miguel Crespo, Adrian Jarabo, Adolfo Muñoz* <br>
SIGGRAPH 2021. [[Project Website](https://mcrespo.me/publications/primary-space-cv/)] [[Paper](https://mcrespo.me/publications/primary-space-cv/data/crespo2021primary.pdf)] [[Official Code](https://github.com/mcrescas/viltrum-mitsuba)]

### EG

**Correlation-aware multiple importance sampling for bidirectional rendering algorithms** <br>
*[Pascal Grittmann](https://graphics.cg.uni-saarland.de/people/grittmann.html), [Iliyan Georgiev](http://www.iliyan.com/), [Philipp Slusallek](https://graphics.cg.uni-saarland.de/slusallek/)* <br>
EG 2021. [[Project Website](http://www.iliyan.com/publications/CorrelationAwareMIS)] [[Paper](http://www.iliyan.com/publications/CorrelationAwareMIS/CorrelationAwareMIS_EG2021.pdf)] [[Official Code](https://github.com/pgrit/MisForCorrelatedBidir)]
## 2020

### SIGGRAPH

**Radiative Backpropagation: An Adjoint Method for Lightning-Fast Differentiable Rendering** <br>
*[Merlin Nimier-David](https://rgl.epfl.ch/people/mnimierdavid), [Sébastien Speierer](https://rgl.epfl.ch/people/speierers), Benoît Ruiz, [Wenzel Jakob](https://rgl.epfl.ch/people/wjakob)*<br>
SIGGRAPH 2020. [[Project Website](https://rgl.epfl.ch/publications/NimierDavid2020Radiative)] [[Paper](https://rgl.s3.eu-central-1.amazonaws.com/media/papers/NimierDavid2020Radiative.pdf)] [[Official Code](https://rgl.s3.eu-central-1.amazonaws.com/media/papers/NimierDavid2020Radiative_1.gz)] [[Unofficial Simple Implementation](https://github.com/ThalesII/differentiable-renderer)]

**Specular Manifold Sampling for Rendering High-Frequency Caustics and Glints** <br>
*[Tizian Zeltner](https://tizianzeltner.com/), [Iliyan Georgiev](http://www.iliyan.com/), [Wenzel Jakob](http://rgl.epfl.ch/people/wjakob)* <br>
SIGGRAPH 2020. [[Project Website](http://rgl.epfl.ch/publications/Zeltner2020Specular)] [[Paper](http://rgl.s3.eu-central-1.amazonaws.com/media/papers/Zeltner2020Specular.pdf)] [[Official Code](https://github.com/tizian/specular-manifold-sampling)]

**Delayed Rejection Metropolis Light Transport** <br>
*[Damien Rioux-Lavoie](https://riouxld21.github.io/research), [Joey Litalien](https://joeylitalien.github.io/), [Adrien Gruson](https://beltegeuse.github.io/research/), [Toshiya Hachisuka](https://www.ci.i.u-tokyo.ac.jp/~hachisuka/), [Derek Nowrouzezahrai](http://www.cim.mcgill.ca/~derek/)* <br>
SIGGRAPH 2020. [[Project Website](https://joeylitalien.github.io/publications/drmlt)] [[Paper](https://joeylitalien.github.io/assets/drmlt/drmlt.pdf)] [[Official Code](https://github.com/joeylitalien/drmlt)]

**Langevin Monte Carlo Rendering with
Gradient-based Adaptation** <br>
*[Fujun Luan](https://www.cs.cornell.edu/~fujun/), [Shuang Zhao](https://shuangz.com/), [Kavita Bala](http://www.cs.cornell.edu/~kb/), [Ioannis Gkioulekas](https://www.cs.cmu.edu/~igkioule/)* <br>
SIGGRAPH 2020. [[Project Website](https://research.cs.cornell.edu/langevin-mcmc/)] [[Paper](https://research.cs.cornell.edu/langevin-mcmc/data/paper.pdf)] [[Official Code](https://github.com/luanfujun/Langevin-MCMC)]

**Path-Space Differentiable Rendering** <br>
*[Cheng Zhang](https://www.ics.uci.edu/~chengz20/), Bailey Miller, Kai Yan, [Ioannis Gkioulekas](https://www.cs.cmu.edu/~igkioule/), [Shuang Zhao](https://shuangz.com/)* <br>
SIGGRAPH 2020. [[Project Website](https://shuangz.com/projects/psdr-sg20/)] [[Paper](https://shuangz.com/projects/psdr-sg20/psdr-sg20.pdf)] [[Official CPU Code](https://shuangz.com/projects/psdr-sg20/psdr-sg20_code.zip)] [[Official GPU Code](https://github.com/uci-rendering/psdr-cuda)]

**Robust Fitting of Parallax-Aware Mixtures for Path Guiding** <br>
*[Lukas Ruppert](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/computergrafik/lehrstuhl/mitarbeiter/lukas-ruppert/), [Sebastian Herholz](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/computergrafik/lehrstuhl/mitarbeiter/ehemalige-mitarbeiter/sebastian-herholz/), [Hendrik P. A. Lensch](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/computergrafik/lehrstuhl/mitarbeiter/prof-dr-ing-hendrik-lensch/)* <br>
SIGGRAPH 2020. [[Project Website](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/computergrafik/lehrstuhl/veroeffentlichungen/publications-since-2012/robust-fitting-of-parallax-aware-mixtures-for-path-guiding/)] [[Paper](https://uni-tuebingen.de/securedl/sdl-eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpYXQiOjE2MjAzMTI4NDQsImV4cCI6MTYyMDQwMjg0MiwidXNlciI6MCwiZ3JvdXBzIjpbMCwtMV0sImZpbGUiOiJmaWxlYWRtaW5cL1VuaV9UdWViaW5nZW5cL0Zha3VsdGFldGVuXC9JbmZvS29nbmlcL1dTSVwvQ29tR3JhcGhcL3B1YmxpY2F0aW9uc1wvMjAyMFwvU0lHR1JBUEhfUm9idXN0UGFyYWxsYXhHdWlkaW5nXC9yb2J1c3RfZml0dGluZ19vZl9wYXJhbGxheF9hd2FyZV9taXh0dXJlc19mb3JfcGF0aF9ndWlkaW5nLnBkZiIsInBhZ2UiOjE3NzMwM30.Vm6iCD97lx42-WWceLUchqBKznu2A1iBvXowkUE0SlU/robust_fitting_of_parallax_aware_mixtures_for_path_guiding.pdf)] [[Official Code](https://github.com/cgtuebingen/robust-vmm-guiding)]

**Resampling-aware Weighting Functions for Bidirectional Path Tracing Using Multiple Light Sub-Paths** <br>
*Kosuke Nabata, [Kei Iwasaki](http://web.wakayama-u.ac.jp/~iwasaki/), [Yoshinori Dobashi](https://ime.ist.hokudai.ac.jp/~doba/)* <br>
SIGGRAPH 2020. [[Project Website](http://web.wakayama-u.ac.jp/~iwasaki/project/risbpt/)] [[Paper](http://web.wakayama-u.ac.jp/~iwasaki/project/risbpt/tog2020.pdf)] [[Official Simple Code](https://github.com/kiwasaki/simple_ris_bpt)]

**Variance-Aware Path Guiding** <br>
*[Alexander Rath](https://graphics.cg.uni-saarland.de/people/rath.html), [Pascal Grittmann](https://graphics.cg.uni-saarland.de/people/grittmann.html), [Sebastian Herholz](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/computergrafik/lehrstuhl/mitarbeiter/sebastian-herholz/), [Petr Vevoda](https://cgg.mff.cuni.cz/~vevoda/), [Philipp Slusallek](https://graphics.cg.uni-saarland.de/people/slusallek.html), [Jaroslav Krivanek](https://cgg.mff.cuni.cz/~jaroslav/)* <br>
SIGGRAPH 2020. [[Project Website](https://graphics.cg.uni-saarland.de/publications/rath-2020-siggraph-guiding.html)] [[Paper](https://graphics.cg.uni-saarland.de/papers/rath-2020-siggraph-guiding-paper.pdf)] [[Official Code](https://github.com/iRath96/variance-aware-path-guiding)]

### SIGGRAPH Asia

**CPPM: Chi-squared Progressive Photon Mapping** <br>
*Zehui Lin, Sheng Li, Xinlu Zeng, Congyi Zhang, Jinzhu Jia, Guoping Wang, [Dinesh Manocha](https://www.cs.umd.edu/people/dmanocha)* <br>
SIGGRAPH Asia 2020. [[Project Website](https://bactlink.github.io/CPPM)] [[Paper](https://bactlink.github.io/CPPM/SIGA2020_CPPM_paper.pdf)] [[Official Code](https://github.com/bacTlink/mitsuba-CPPM)]

**Path Tracing Estimators for Refractive Radiative Transfer** <br>
*[Adithya Pediredla](https://www.ri.cmu.edu/ri-people/adithya-pediredla/), Yasin Karimi Chalmiani, [Matteo Giuseppe Scopelliti](https://users.ece.cmu.edu/~mchamanz/Members.html), [Maysam Chamanzar](https://www.ece.cmu.edu/directory/bios/chamanzar-maysam.html), [Srinivasa Narasimhan](https://www.cs.cmu.edu/~srinivas/), [Ioannis Gkioulekas](https://www.cs.cmu.edu/~igkioule/)* <br>
SIGGRAPH Asia 2020. [[Project Website](https://imaging.cs.cmu.edu/rrte/)] [[Paper](https://imaging.cs.cmu.edu/rrte/assets/Renderer_AuthorCopy.pdf)] [[Official Code](https://github.com/cmu-ci-lab/MitsubaER)]


### EG

**Stratified Markov Chain Monte Carlo Light Transport** <br>
*[Adrien Gruson](https://beltegeuse.github.io/research/), Rex West, [Toshiya Hachisuka](https://cs.uwaterloo.ca/~thachisu/)* <br>
EG 2020. [[Paper](https://cs.uwaterloo.ca/~thachisu/smcmc.pdf)] [[Official Code in Mitsuba](https://github.com/beltegeuse/smcmc)] [[Official Code in Rust](https://github.com/beltegeuse/rustlight/blob/master/src/integrators/mcmc/smcmc.rs)] [[Unoffcial Code](https://github.com/shiinamiyuki/AkariRender/blob/master/src/akari/render_smcmc.cpp)]

## 2019

### SIGGRAPH

**A null-scattering path integral formulation of light transport** <br>
*[Bailey Miller](https://www.bailey-miller.com/), [Iliyan Georgiev](http://iliyan.com/), [Wojciech Jarosz](https://www.cs.dartmouth.edu/~wjarosz/)* <br>
SIGGRAPH 2019. [[Project Website](https://cs.dartmouth.edu/~wjarosz/publications/miller19null.html)] [[Paper](https://cs.dartmouth.edu/~wjarosz/publications/miller19null.pdf)] [[Code](https://github.com/baileymiller/nullpath)]

### SIGGRAPH Asia

**Integral formulations of volumetric transmittance** <br>
*[Iliyan Georgiev](http://iliyan.com/), [Zackary Misso](http://zackmisso.com/), [Toshiya Hachisuka](https://www.ci.i.u-tokyo.ac.jp/~hachisuka/), [Derek Nowrouzezahrai](http://www.cim.mcgill.ca/~derek/), [Jaroslav Křivánek](http://cgg.mff.cuni.cz/~jaroslav/), [Wojciech Jarosz](https://www.cs.dartmouth.edu/~wjarosz/)* <br>
SIGGRAPH 2019. [[Project Website](https://cs.dartmouth.edu/~wjarosz/publications/georgiev19integral.html)] [[Paper](https://cs.dartmouth.edu/~wjarosz/publications/georgiev19integral.pdf)] [[Code](https://github.com/ZackMisso/TransmittanceEstimation)]

**Variance-Aware Multiple Importance Sampling** <br>
*[Pascal Grittmann](https://graphics.cg.uni-saarland.de/people/grittmann.html), [Iliyan Georgiev](http://iliyan.com/), [Philipp Slusallek](https://graphics.cg.uni-saarland.de/people/slusallek.html), [Jaroslav Křivánek](http://cgg.mff.cuni.cz/~jaroslav/)* <br>
SIGGRAPH Asia 2019. [[Project Website](https://cgg.mff.cuni.cz/~jaroslav/papers/2019-variance-aware-mis/index.html)] [[Paper](https://cgg.mff.cuni.cz/~jaroslav/papers/2019-variance-aware-mis/2019-grittmann-variance-aware-mis-paper.pdf)] [[Official Code](https://github.com/pgrit/var-aware-mis-pbrt)]

## 2018

### SIGGRAPH Asia

**A radiative transfer framework for non-exponential media** <br>
*[Benedikt Bitterli](http://benedikt-bitterli.me/) [Srinath Ravichandran](https://www.cs.dartmouth.edu/~sriravic/) [Thomas Müller](https://tom94.net/) [Magnus Wrenninge](http://magnuswrenninge.com/) [Jan Novák](http://drz.disneyresearch.com/~jnovak/) [Steve Marschner](http://www.cs.cornell.edu/~srm/) [Wojciech Jarosz](https://www.cs.dartmouth.edu/~wjarosz/)*<br>
SIGGRAPH Asia 2018. [[Project Website](https://cs.dartmouth.edu/~wjarosz/publications/bitterli18framework.html)] [[Paper](https://cs.dartmouth.edu/~wjarosz/publications/bitterli18framework.pdf)] [[Official Code](https://github.com/tunabrain/tungsten/commit/98b366d5ddd43eaa9ee476a12ae364bedda2f94e)]
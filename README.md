# PyTorch in Unreal Engine (PyTuech)

<p align="center">
  <img src="https://github.com/gpt-3d/pytuech/assets/20903421/7774b547-5170-4574-9763-0f426c3a5cce?raw=true" alt="pytuech"/>
</p>

### What is this?

Pronouned "Pie-Tyooch"

This project exists to extend on [P1ayer-1's](https://github.com/P1ayer-1) efforts of integrating PyTorch into Unreal Engine, and serves as a way to unify the dependencies, make his tutorials easier to understand at a glance (dive deep by watching them!), and to build examples that can be shared with everyone. See the [wiki](https://github.com/gpt-3d/pytorch/wiki) for project and plugin setup, or use the quickstart below to get moving immediately!

**See these videos for how this is all working together!**
> [How to use LibTorch and Tokenizers in Unreal Engine 5](https://www.youtube.com/watch?v=dvGWUh4SPBY)

> 
> [How to use Meta's Llama in Unreal Engine 5](https://www.youtube.com/watch?v=0YI2O5uSuFw)


## Quickstart

`git clone https://github.com/gpt-3d/pytuech.git`
 
`cd pytorch`
  
`git submodule update --init --recursive`

You just **blazed** through the first step of the wiki, good job! Start on [Step 2](https://github.com/gpt-3d/pytorch/wiki/2.-LibTorch-Plugin-Setup) to setup your plugins to point to your desired PyTorch library...


### Credits

This project contains submodules;
- [Libtorch-UE5](https://github.com/P1ayer-1/Libtorch-UE5) plugin that is extended from [UE-ATUM](https://github.com/UE-ATUM/Plugin)
- [Tokenizers-UE5](https://github.com/P1ayer-1/Tokenizers-UE5), a modification of a Hugging Face cpp tokenizers library based off [mlc-ai tokenizers-cpp](https://github.com/mlc-ai/tokenizers-cpp), as a plugin in Unreal Engine. 

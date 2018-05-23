# ScriptableRenderPipeline
**Unity 2018.1.0f2 ScriptableRenderPipeline** <BR/><BR/>


### ShaderBlurMoments.compute
If you have this bug, You can download fixed version here.<BR/>
 > Shader error in 'ShadowBlurMoments.compute': All kernels must use same constant buffer layouts; 'blurWeightsStorage' property found to be different
- Test<BR/>
 Switch platform to Android<BR/>
<BR/>
- Download<BR/>
/ScriptableRenderPipeline/Core/CoreRP/Shadow/ShadowBlurMoments.compute<BR/>
Original: 
https://github.com/Unity-Technologies/ScriptableRenderPipeline/blob/master/ScriptableRenderPipeline/Core/CoreRP/Shadow/ShadowBlurMoments.compute
<BR/>
<BR/>

### Point light
First point light is not working in Script Renderpipeline Tag: 2018.1.0f2.<BR/>
It was fixed in master version (https://github.com/Unity-Technologies/ScriptableRenderPipeline/pull/1216).<BR/>
If you download Tag 2018.1.0f2 (https://github.com/Unity-Technologies/ScriptableRenderPipeline/tree/2018.1.0f2), download it only.<BR/>
- Test<BR/>
 1. new scene<BR/>
 1. add sphere(or other primitive), set LightweightShader.shader<BR/>
 1. add point light -> no affected<BR/>
 1. add one more point light -> affected.<BR/>
<BR/>
- Download<BR/>
/ScriptableRenderPipeline/LightweightPipeline/LWRP/LightweightPipeline.cs<BR/>
Original: https://github.com/Unity-Technologies/ScriptableRenderPipeline/blob/2018.1.0f2/ScriptableRenderPipeline/LightweightPipeline/LWRP/LightweightPipeline.cs
<BR/>
<BR/>
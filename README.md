# ScriptableRenderPipeline
**Unity 2018.1.0f2 ScriptableRenderPipeline** <BR/><BR/>

### Point light
First point light is not working in Unity 2018.1.0f2 Lightweight RenderPipeline. It was fixed in Master Version.<BR/>
I fix for SRP 2018.1.0f2 (https://github.com/Unity-Technologies/ScriptableRenderPipeline/tree/2018.1.0f2)<BR/>
- Test<BR/>
1. new scene<BR/>
2. add sphere(or other primitive), set LightweightShader.shader<BR/>
3. add point light -> no affected<BR/>
4. add one more point light -> affected.<BR/>
<BR/>
- Download<BR/>
/ScriptableRenderPipeline/LightweightPipeline/LWRP/LightweightPipeline.cs<BR/>
Original: https://github.com/Unity-Technologies/ScriptableRenderPipeline/blob/2018.1.0f2/ScriptableRenderPipeline/LightweightPipeline/LWRP/LightweightPipeline.cs
<BR/>
<BR/>
### ShaderBlurMoments.compute
If you have this bug, You can download fixed version here.<BR/>
 > Shader error in 'ShadowBlurMoments.compute': All kernels must use same constant buffer layouts; 'blurWeightsStorage' property found to be different
- Test<BR/>
 Switch platform to Android.<BR/>
<BR/>
- Download<BR/>
/ScriptableRenderPipeline/Core/CoreRP/Shadow/ShadowBlurMoments.compute<BR/>
Original: 
https://github.com/Unity-Technologies/ScriptableRenderPipeline/blob/master/ScriptableRenderPipeline/Core/CoreRP/Shadow/ShadowBlurMoments.compute
<BR/>
<BR/>
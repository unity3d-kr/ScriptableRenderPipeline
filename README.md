# ScriptableRenderPipeline
**Unity 2018.1.0f2 ScriptableRenderPipeline**<BR/>
It can't express point light in LWRP.<BR/>
test:<BR/>
1. new scene<BR/>
2. add sphere(or other primitive), set LightweightShader.shader<BR/>
3. add point light -> no expression.<BR/>
4. add one more point light -> expression.<BR/>
<BR/>
So, I fix it.<BR/>
Original: (Tag: 2018.1.0f2)<BR/>
https://github.com/Unity-Technologies/ScriptableRenderPipeline/blob/master/ScriptableRenderPipeline/LightweightPipeline/LWRP/LightweightPipeline.cs<BR/>
<BR/>

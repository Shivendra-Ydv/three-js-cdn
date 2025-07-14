
```
three-js-cdn
├─ docs
│  └─ talkinghead
│     ├─ addons
│     │  ├─ DRACOLoader.js
│     │  ├─ FBXLoader.js
│     │  ├─ GLTFLoader.js
│     │  ├─ libs
│     │  │  ├─ curves
│     │  │  │  └─ NURBSCurve.js
│     │  │  ├─ fflate.module.js
│     │  │  └─ stats.module.js
│     │  ├─ OrbitControls.js
│     │  ├─ RoomEnvironment.js
│     │  └─ utils
│     │     └─ BufferGeometryUtils.js
│     ├─ dynamicbones.mjs
│     ├─ playback-worklet.js
│     ├─ talkinghead.mjs
│     └─ three.module.js
└─ README.md

```
```
three-js-cdn
├─ docs
│  └─ TalkingHead
│     ├─ dynamicbones.mjs
│     ├─ examples
│     │  └─ jsm
│     │     ├─ Addons.js
│     │     ├─ animation
│     │     │  ├─ AnimationClipCreator.js
│     │     │  ├─ CCDIKSolver.js
│     │     │  ├─ MMDAnimationHelper.js
│     │     │  └─ MMDPhysics.js
│     │     ├─ capabilities
│     │     │  ├─ WebGL.js
│     │     │  └─ WebGPU.js
│     │     ├─ controls
│     │     │  ├─ ArcballControls.js
│     │     │  ├─ DragControls.js
│     │     │  ├─ FirstPersonControls.js
│     │     │  ├─ FlyControls.js
│     │     │  ├─ MapControls.js
│     │     │  ├─ OrbitControls.js
│     │     │  ├─ PointerLockControls.js
│     │     │  ├─ TrackballControls.js
│     │     │  └─ TransformControls.js
│     │     ├─ csm
│     │     │  ├─ CSM.js
│     │     │  ├─ CSMFrustum.js
│     │     │  ├─ CSMHelper.js
│     │     │  ├─ CSMShader.js
│     │     │  └─ CSMShadowNode.js
│     │     ├─ curves
│     │     │  ├─ CurveExtras.js
│     │     │  ├─ NURBSCurve.js
│     │     │  ├─ NURBSSurface.js
│     │     │  ├─ NURBSUtils.js
│     │     │  └─ NURBSVolume.js
│     │     ├─ effects
│     │     │  ├─ AnaglyphEffect.js
│     │     │  ├─ AsciiEffect.js
│     │     │  ├─ OutlineEffect.js
│     │     │  ├─ ParallaxBarrierEffect.js
│     │     │  ├─ PeppersGhostEffect.js
│     │     │  └─ StereoEffect.js
│     │     ├─ environments
│     │     │  ├─ DebugEnvironment.js
│     │     │  └─ RoomEnvironment.js
│     │     ├─ exporters
│     │     │  ├─ DRACOExporter.js
│     │     │  ├─ EXRExporter.js
│     │     │  ├─ GLTFExporter.js
│     │     │  ├─ KTX2Exporter.js
│     │     │  ├─ MMDExporter.js
│     │     │  ├─ OBJExporter.js
│     │     │  ├─ PLYExporter.js
│     │     │  ├─ STLExporter.js
│     │     │  └─ USDZExporter.js
│     │     ├─ geometries
│     │     │  ├─ BoxLineGeometry.js
│     │     │  ├─ ConvexGeometry.js
│     │     │  ├─ DecalGeometry.js
│     │     │  ├─ InstancedPointsGeometry.js
│     │     │  ├─ ParametricGeometries.js
│     │     │  ├─ ParametricGeometry.js
│     │     │  ├─ RoundedBoxGeometry.js
│     │     │  ├─ TeapotGeometry.js
│     │     │  └─ TextGeometry.js
│     │     ├─ helpers
│     │     │  ├─ LightProbeHelper.js
│     │     │  ├─ LightProbeHelperGPU.js
│     │     │  ├─ OctreeHelper.js
│     │     │  ├─ PositionalAudioHelper.js
│     │     │  ├─ RectAreaLightHelper.js
│     │     │  ├─ TextureHelper.js
│     │     │  ├─ TextureHelperGPU.js
│     │     │  ├─ VertexNormalsHelper.js
│     │     │  ├─ VertexTangentsHelper.js
│     │     │  └─ ViewHelper.js
│     │     ├─ interactive
│     │     │  ├─ HTMLMesh.js
│     │     │  ├─ InteractiveGroup.js
│     │     │  ├─ SelectionBox.js
│     │     │  └─ SelectionHelper.js
│     │     ├─ libs
│     │     │  ├─ ammo.wasm.js
│     │     │  ├─ ammo.wasm.wasm
│     │     │  ├─ basis
│     │     │  │  ├─ basis_transcoder.js
│     │     │  │  ├─ basis_transcoder.wasm
│     │     │  │  └─ README.md
│     │     │  ├─ chevrotain.module.min.js
│     │     │  ├─ draco
│     │     │  │  ├─ draco_decoder.js
│     │     │  │  ├─ draco_decoder.wasm
│     │     │  │  ├─ draco_encoder.js
│     │     │  │  ├─ draco_wasm_wrapper.js
│     │     │  │  ├─ gltf
│     │     │  │  │  ├─ draco_decoder.js
│     │     │  │  │  ├─ draco_decoder.wasm
│     │     │  │  │  ├─ draco_encoder.js
│     │     │  │  │  └─ draco_wasm_wrapper.js
│     │     │  │  └─ README.md
│     │     │  ├─ ecsy.module.js
│     │     │  ├─ fflate.module.js
│     │     │  ├─ ktx-parse.module.js
│     │     │  ├─ lil-gui.module.min.js
│     │     │  ├─ lottie_canvas.module.js
│     │     │  ├─ meshopt_decoder.module.js
│     │     │  ├─ mikktspace.module.js
│     │     │  ├─ mmdparser.module.js
│     │     │  ├─ motion-controllers.module.js
│     │     │  ├─ opentype.module.js
│     │     │  ├─ potpack.module.js
│     │     │  ├─ rhino3dm
│     │     │  │  ├─ rhino3dm.js
│     │     │  │  ├─ rhino3dm.module.js
│     │     │  │  └─ rhino3dm.wasm
│     │     │  ├─ stats.module.js
│     │     │  ├─ surfaceNet.js
│     │     │  ├─ tween.module.js
│     │     │  ├─ utif.module.js
│     │     │  └─ zstddec.module.js
│     │     ├─ lighting
│     │     │  └─ TiledLighting.js
│     │     ├─ lights
│     │     │  ├─ LightProbeGenerator.js
│     │     │  ├─ RectAreaLightTexturesLib.js
│     │     │  └─ RectAreaLightUniformsLib.js
│     │     ├─ lines
│     │     │  ├─ Line2.js
│     │     │  ├─ LineGeometry.js
│     │     │  ├─ LineMaterial.js
│     │     │  ├─ LineSegments2.js
│     │     │  ├─ LineSegmentsGeometry.js
│     │     │  ├─ webgpu
│     │     │  │  ├─ Line2.js
│     │     │  │  ├─ LineSegments2.js
│     │     │  │  └─ Wireframe.js
│     │     │  ├─ Wireframe.js
│     │     │  └─ WireframeGeometry2.js
│     │     ├─ loaders
│     │     │  ├─ 3DMLoader.js
│     │     │  ├─ 3MFLoader.js
│     │     │  ├─ AMFLoader.js
│     │     │  ├─ BVHLoader.js
│     │     │  ├─ ColladaLoader.js
│     │     │  ├─ DDSLoader.js
│     │     │  ├─ DRACOLoader.js
│     │     │  ├─ EXRLoader.js
│     │     │  ├─ FBXLoader.js
│     │     │  ├─ FontLoader.js
│     │     │  ├─ GCodeLoader.js
│     │     │  ├─ GLTFLoader.js
│     │     │  ├─ HDRCubeTextureLoader.js
│     │     │  ├─ IESLoader.js
│     │     │  ├─ KMZLoader.js
│     │     │  ├─ KTX2Loader.js
│     │     │  ├─ KTXLoader.js
│     │     │  ├─ LDrawLoader.js
│     │     │  ├─ LottieLoader.js
│     │     │  ├─ LUT3dlLoader.js
│     │     │  ├─ LUTCubeLoader.js
│     │     │  ├─ LUTImageLoader.js
│     │     │  ├─ lwo
│     │     │  │  ├─ IFFParser.js
│     │     │  │  ├─ LWO2Parser.js
│     │     │  │  └─ LWO3Parser.js
│     │     │  ├─ LWOLoader.js
│     │     │  ├─ MaterialXLoader.js
│     │     │  ├─ MD2Loader.js
│     │     │  ├─ MDDLoader.js
│     │     │  ├─ MMDLoader.js
│     │     │  ├─ MTLLoader.js
│     │     │  ├─ NRRDLoader.js
│     │     │  ├─ OBJLoader.js
│     │     │  ├─ PCDLoader.js
│     │     │  ├─ PDBLoader.js
│     │     │  ├─ PLYLoader.js
│     │     │  ├─ PVRLoader.js
│     │     │  ├─ RGBELoader.js
│     │     │  ├─ RGBMLoader.js
│     │     │  ├─ STLLoader.js
│     │     │  ├─ SVGLoader.js
│     │     │  ├─ TDSLoader.js
│     │     │  ├─ TGALoader.js
│     │     │  ├─ TIFFLoader.js
│     │     │  ├─ TTFLoader.js
│     │     │  ├─ UltraHDRLoader.js
│     │     │  ├─ USDZLoader.js
│     │     │  ├─ VOXLoader.js
│     │     │  ├─ VRMLLoader.js
│     │     │  ├─ VTKLoader.js
│     │     │  └─ XYZLoader.js
│     │     ├─ materials
│     │     │  ├─ LDrawConditionalLineMaterial.js
│     │     │  ├─ LDrawConditionalLineNodeMaterial.js
│     │     │  ├─ MeshGouraudMaterial.js
│     │     │  └─ MeshPostProcessingMaterial.js
│     │     ├─ math
│     │     │  ├─ Capsule.js
│     │     │  ├─ ColorConverter.js
│     │     │  ├─ ColorSpaces.js
│     │     │  ├─ ConvexHull.js
│     │     │  ├─ ImprovedNoise.js
│     │     │  ├─ Lut.js
│     │     │  ├─ MeshSurfaceSampler.js
│     │     │  ├─ OBB.js
│     │     │  ├─ Octree.js
│     │     │  └─ SimplexNoise.js
│     │     ├─ misc
│     │     │  ├─ ConvexObjectBreaker.js
│     │     │  ├─ GPUComputationRenderer.js
│     │     │  ├─ Gyroscope.js
│     │     │  ├─ MD2Character.js
│     │     │  ├─ MD2CharacterComplex.js
│     │     │  ├─ MorphAnimMesh.js
│     │     │  ├─ MorphBlendMesh.js
│     │     │  ├─ ProgressiveLightMap.js
│     │     │  ├─ ProgressiveLightMapGPU.js
│     │     │  ├─ RollerCoaster.js
│     │     │  ├─ Timer.js
│     │     │  ├─ TubePainter.js
│     │     │  ├─ Volume.js
│     │     │  └─ VolumeSlice.js
│     │     ├─ modifiers
│     │     │  ├─ CurveModifier.js
│     │     │  ├─ CurveModifierGPU.js
│     │     │  ├─ EdgeSplitModifier.js
│     │     │  ├─ SimplifyModifier.js
│     │     │  └─ TessellateModifier.js
│     │     ├─ objects
│     │     │  ├─ GroundedSkybox.js
│     │     │  ├─ InstancedPoints.js
│     │     │  ├─ Lensflare.js
│     │     │  ├─ LensflareMesh.js
│     │     │  ├─ MarchingCubes.js
│     │     │  ├─ Reflector.js
│     │     │  ├─ ReflectorForSSRPass.js
│     │     │  ├─ Refractor.js
│     │     │  ├─ ShadowMesh.js
│     │     │  ├─ Sky.js
│     │     │  ├─ SkyMesh.js
│     │     │  ├─ Water.js
│     │     │  ├─ Water2.js
│     │     │  ├─ Water2Mesh.js
│     │     │  └─ WaterMesh.js
│     │     ├─ offscreen
│     │     │  ├─ jank.js
│     │     │  ├─ offscreen.js
│     │     │  └─ scene.js
│     │     ├─ physics
│     │     │  ├─ AmmoPhysics.js
│     │     │  ├─ JoltPhysics.js
│     │     │  └─ RapierPhysics.js
│     │     ├─ postprocessing
│     │     │  ├─ AfterimagePass.js
│     │     │  ├─ BloomPass.js
│     │     │  ├─ BokehPass.js
│     │     │  ├─ ClearPass.js
│     │     │  ├─ CubeTexturePass.js
│     │     │  ├─ DotScreenPass.js
│     │     │  ├─ EffectComposer.js
│     │     │  ├─ FilmPass.js
│     │     │  ├─ GlitchPass.js
│     │     │  ├─ GTAOPass.js
│     │     │  ├─ HalftonePass.js
│     │     │  ├─ LUTPass.js
│     │     │  ├─ MaskPass.js
│     │     │  ├─ OutlinePass.js
│     │     │  ├─ OutputPass.js
│     │     │  ├─ Pass.js
│     │     │  ├─ RenderPass.js
│     │     │  ├─ RenderPixelatedPass.js
│     │     │  ├─ RenderTransitionPass.js
│     │     │  ├─ SAOPass.js
│     │     │  ├─ SavePass.js
│     │     │  ├─ ShaderPass.js
│     │     │  ├─ SMAAPass.js
│     │     │  ├─ SSAARenderPass.js
│     │     │  ├─ SSAOPass.js
│     │     │  ├─ SSRPass.js
│     │     │  ├─ TAARenderPass.js
│     │     │  ├─ TexturePass.js
│     │     │  └─ UnrealBloomPass.js
│     │     ├─ renderers
│     │     │  ├─ CSS2DRenderer.js
│     │     │  ├─ CSS3DRenderer.js
│     │     │  ├─ Projector.js
│     │     │  └─ SVGRenderer.js
│     │     ├─ shaders
│     │     │  ├─ ACESFilmicToneMappingShader.js
│     │     │  ├─ AfterimageShader.js
│     │     │  ├─ BasicShader.js
│     │     │  ├─ BleachBypassShader.js
│     │     │  ├─ BlendShader.js
│     │     │  ├─ BokehShader.js
│     │     │  ├─ BokehShader2.js
│     │     │  ├─ BrightnessContrastShader.js
│     │     │  ├─ ColorCorrectionShader.js
│     │     │  ├─ ColorifyShader.js
│     │     │  ├─ ConvolutionShader.js
│     │     │  ├─ CopyShader.js
│     │     │  ├─ DepthLimitedBlurShader.js
│     │     │  ├─ DigitalGlitch.js
│     │     │  ├─ DOFMipMapShader.js
│     │     │  ├─ DotScreenShader.js
│     │     │  ├─ ExposureShader.js
│     │     │  ├─ FilmShader.js
│     │     │  ├─ FocusShader.js
│     │     │  ├─ FreiChenShader.js
│     │     │  ├─ FXAAShader.js
│     │     │  ├─ GammaCorrectionShader.js
│     │     │  ├─ GodRaysShader.js
│     │     │  ├─ GTAOShader.js
│     │     │  ├─ HalftoneShader.js
│     │     │  ├─ HorizontalBlurShader.js
│     │     │  ├─ HorizontalTiltShiftShader.js
│     │     │  ├─ HueSaturationShader.js
│     │     │  ├─ KaleidoShader.js
│     │     │  ├─ LuminosityHighPassShader.js
│     │     │  ├─ LuminosityShader.js
│     │     │  ├─ MirrorShader.js
│     │     │  ├─ MMDToonShader.js
│     │     │  ├─ NormalMapShader.js
│     │     │  ├─ OutputShader.js
│     │     │  ├─ PoissonDenoiseShader.js
│     │     │  ├─ RGBShiftShader.js
│     │     │  ├─ SAOShader.js
│     │     │  ├─ SepiaShader.js
│     │     │  ├─ SMAAShader.js
│     │     │  ├─ SobelOperatorShader.js
│     │     │  ├─ SSAOShader.js
│     │     │  ├─ SSRShader.js
│     │     │  ├─ SubsurfaceScatteringShader.js
│     │     │  ├─ TechnicolorShader.js
│     │     │  ├─ ToonShader.js
│     │     │  ├─ TriangleBlurShader.js
│     │     │  ├─ UnpackDepthRGBAShader.js
│     │     │  ├─ VelocityShader.js
│     │     │  ├─ VerticalBlurShader.js
│     │     │  ├─ VerticalTiltShiftShader.js
│     │     │  ├─ VignetteShader.js
│     │     │  ├─ VolumeShader.js
│     │     │  └─ WaterRefractionShader.js
│     │     ├─ textures
│     │     │  └─ FlakesTexture.js
│     │     ├─ transpiler
│     │     │  ├─ AST.js
│     │     │  ├─ GLSLDecoder.js
│     │     │  ├─ ShaderToyDecoder.js
│     │     │  ├─ Transpiler.js
│     │     │  └─ TSLEncoder.js
│     │     ├─ tsl
│     │     │  ├─ display
│     │     │  │  ├─ AfterImageNode.js
│     │     │  │  ├─ AnaglyphPassNode.js
│     │     │  │  ├─ AnamorphicNode.js
│     │     │  │  ├─ BleachBypass.js
│     │     │  │  ├─ BloomNode.js
│     │     │  │  ├─ DenoiseNode.js
│     │     │  │  ├─ DepthOfFieldNode.js
│     │     │  │  ├─ DotScreenNode.js
│     │     │  │  ├─ FilmNode.js
│     │     │  │  ├─ FXAANode.js
│     │     │  │  ├─ GaussianBlurNode.js
│     │     │  │  ├─ GTAONode.js
│     │     │  │  ├─ hashBlur.js
│     │     │  │  ├─ LensflareNode.js
│     │     │  │  ├─ Lut3DNode.js
│     │     │  │  ├─ MotionBlur.js
│     │     │  │  ├─ OutlineNode.js
│     │     │  │  ├─ ParallaxBarrierPassNode.js
│     │     │  │  ├─ PixelationPassNode.js
│     │     │  │  ├─ RGBShiftNode.js
│     │     │  │  ├─ Sepia.js
│     │     │  │  ├─ SMAANode.js
│     │     │  │  ├─ SobelOperatorNode.js
│     │     │  │  ├─ SSAAPassNode.js
│     │     │  │  ├─ SSRNode.js
│     │     │  │  ├─ StereoCompositePassNode.js
│     │     │  │  ├─ StereoPassNode.js
│     │     │  │  ├─ TRAAPassNode.js
│     │     │  │  └─ TransitionNode.js
│     │     │  └─ lighting
│     │     │     └─ TiledLightsNode.js
│     │     ├─ utils
│     │     │  ├─ BufferGeometryUtils.js
│     │     │  ├─ CameraUtils.js
│     │     │  ├─ GeometryCompressionUtils.js
│     │     │  ├─ GeometryUtils.js
│     │     │  ├─ LDrawUtils.js
│     │     │  ├─ SceneUtils.js
│     │     │  ├─ ShadowMapViewer.js
│     │     │  ├─ ShadowMapViewerGPU.js
│     │     │  ├─ SkeletonUtils.js
│     │     │  ├─ SortUtils.js
│     │     │  ├─ UVsDebug.js
│     │     │  ├─ WebGLTextureUtils.js
│     │     │  ├─ WebGPUTextureUtils.js
│     │     │  └─ WorkerPool.js
│     │     └─ webxr
│     │        ├─ ARButton.js
│     │        ├─ OculusHandModel.js
│     │        ├─ OculusHandPointerModel.js
│     │        ├─ Text2D.js
│     │        ├─ VRButton.js
│     │        ├─ XRButton.js
│     │        ├─ XRControllerModelFactory.js
│     │        ├─ XREstimatedLight.js
│     │        ├─ XRHandMeshModel.js
│     │        ├─ XRHandModelFactory.js
│     │        ├─ XRHandPrimitiveModel.js
│     │        └─ XRPlanes.js
│     ├─ playback-worklet.js
│     ├─ talkinghead.mjs
│     └─ three.module.js
└─ README.md

```
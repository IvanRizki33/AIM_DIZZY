# AIM_DIZZY
Pembuat file config PubgMobile


[SystemSettings]
	r.AllowHDR
	r.Vsync=0
	r.PUBGMaxSupportQualityLevel=3
	r.PUBGDeviceFPSLow=90
	r.PUBGDeviceFPSMid=90
	r.PUBGDeviceFPSHigh=90
	r.PUBGDeviceFPSHDR=90
	r.PUBGDeviceFPSUltraHDR=90

[/Script/ⒾⓋⒶⓃ_ⓇⒾⓏⓀⒾ_ⓅⓇⒶⓉⒶⓂⒶ_Ⓟ]

[BasicSettings]
	AimAssist=True
	Aim Assist=True
	r.AimAssist=9.9f
	r.hit=9.9f
	AimAssist=9.9f
	DamageHit=9f
	Crosshair=6f
	HeadHit=6f

[SystemSettings]
	DetailMode=0
	EffectsLevel=0
	Distortion=true
	UseVsync=true
	Fullscreen=true
	LensFlares=true
	MotionBlur=true
	DynamicLights=true
	bAllowLightShafts=true
	DynamicShadows=true
	AmbientOcclusion=true
	bEnableVSMShadows=true
	CompositeDynamicLights=false
	AllowSubsurfaceScattering=true
	bEnableBranchingPCFShadows=true
	bAllowHardwareShadowFiltering=true
	bEnableForegroundSelfShadowing=true
	bEnableForegroundShadowsOnWorld=true

[FoliageQuality]
	grass.DensityScale=0.1
	foliage.DensityScale=1.0
	r.ViewFoliageDistance=80000

[ConsoleVariables]
	ParticleLODBias=0
	r.Shaders.Optimize=0
	SpeedTreeLODBias=-1
	StaticMeshLODBias=-1
	r.TextureStreaming=True
	BasenameProfile=AIM_Esport.Dizzy
	SkeletalMeshLODBias=-1
	MaxDrawDistanceScale=10
	r.Shaders.KeepDebugInfo=1
	r.MobileContentScaleFactor=0.9
	r.Streaming.MaxTempMemoryAllowed=1
	AutoAimEnable=Max

[ViewDistanceQuality]
	r.ViewDistanceScale=1.0
	r.SkeletalMeshLODBias=0
	b.NetMoveEnableByDistance=-1
	b.LevelStreamingMaxLODLevel=3
	b.LevelStreamingDistanceRatioForLOD=1.0

[Engine.Engine]
	Bloom=true
	UseVsync=true
	Distortion=true
	Fullscreen=true
	LensFlares=true
	MotionBlur=true
	FogVolumes=true
	DepthOfField=true
	DynamicLights=true
	AmbientOcclusion=true
	DisableSphericalHarmonicLights=false

[SlateRenderer]
	NumPreallocatedVertices=10000

[/Script/Engine.Fps]
	Stable.Fps=True

[/Script/Engine.Basic]
	T.SpeedFire=High
	T.Long=High
	T.Speed=High
	T.LongJump=False

[Basename.Profile]
	b.AIM_Esport.Dizzy

[EffectsQuality]
	r.SSS.Scale=1
	r.SSS.Quality=0
	r.SSR.Quality=0
	r.DetailMode=0
	r.SSS.HalfRes=0
	r.SSS.SampleSet=2
	r.RefractionQuality=1
	r.SceneColorFormat=4
	r.ParticleLightQuality=2
	r.MaterialQualityLevel=1
	r.TranslucencyVolumeBlur=1
	r.EmitterSpawnRateScale=1.0
	r.TranslucencyLightingVolumeDim=64

[/Script/Engine.UserInterfaceSettings]
	CrosshairsCursor=True
	RenderFocusRule=NavigationOnly

[Auto Aim Trace]
	AimAssist=True
	r.Target=Enemy
	r.Radius=400

[SystemSettings]
	r.ACESStyle=4
	r.DetailMode=0
	r.MobileHDR=0.0
	foliage.MinLOD=1
	r.PUBGVersion=5
	r.ShadowQuality=0
	r.MobileMSAA=1.0
	r.MSAACount=4.0
	r.UserHDRSetting=4
	r.UserMSAASetting=0
	r.RefractionQuality=0
	r.UserVulkanSetting=1
	r.UserQualitySetting=0
	r.UserShadowSwitch=1
	r.Mobile.EnablePPR=0.0
	r.MaterialQualityLevel=0
	r.DepthOfFieldQuality=0
	r.MobileSimpleShader=0
	r.TextureStreaming=True
	r.EmitterSpawnRateScale=0.5
	foliage.LODDistanceScale=0.5
	r.MaterialQualitySuperHigh=0.0
	r.Mobile.SceneColorFormat=0.0
	r.DefaultFeature.AntiAliasing=0.0
	r.StaticMeshLODDistanceScale=0.5
	r.MobileNumDynamicPointLights=0
	r.Mobile.EnableMovableSpotlights=0

[TextureStreaming]
	MinTextureResidentMipCount=8
	r.TextureStreaming=True

[/Script/Engine.NetworkSettings]
	n.VerifyPeer=True

[PostProcessQuality]
	r.HBAO.Enable=1
	r.BloomQuality=3
	r.Upscale.Quality=1
	r.LensFlareQuality=0
	r.LightShaftQuality=0
	r.Filter.SizeScale=0.6
	r.MotionBlurQuality=0
	r.FastBlurThreshold=0
	r.Tonemapper.Quality=2
	r.DepthOfFieldQuality=0
	r.EyeAdaptationQuality=1
	r.Tonemapper.Sharpen=0
	r.RenderTargetPoolMin=300
	r.AmbientOcclusionLevels=0
	r.SceneColorFringeQuality=0
	r.AmbientOcclusionMaxQuality=0
	r.Tonemapper.GrainQuantization=0
	r.AmbientOcclusionRadiusScale=1.2
	r.AmbientOcclusionMipLevelFactor=1.0

[ScalabilityGroups]
	Sg.ResolutionQuality=58
	Sg.ViewDistanceQuality=1
	Sg.AntiAliasingQuality=1
	Sg.ShadowQuality=1
	Sg.PostProcessQuality=3
	Sg.TextureQuality=0
	Sg.EffectsQuality=0
	Sg.FoliageQuality=0
	Sg.TrueSkyQuality=0
	Sg.GroundClutterQuality=1
	Sg.IBLQuality=0
	Sg.FrameRateLimit=60
	Sg.FrameRateCap=1
	Sg.MSAA.CompositingSampleCount=1

[/Script/Engine.Engine]
	MipFadeInSpeed1=0.0
	MinTextureDensity=0.0
	IdealTextureDensity=1.0
	MaxTextureDensity=1.0
	MipFadeOutSpeed1=0.0
	MipFadeInSpeed0=0.0
	MipFadeOutSpeed0=0.0
	MaxLightMapDensity=0.0
	IdealLightMapDensity=0.0
	MinSmoothedFrameRate=60
	MaxSmoothedFrameRate=120
	bCombineSimilarMappings=True
	bUseBackgroundLevelStreaming=False

[/Script/ⒾⓋⒶⓃ_ⓇⒾⓏⓀⒾ_ⓅⓇⒶⓉⒶⓂⒶ_Ⓟ]

[/Script/ShadowTrackerExtra.STExtraBaseCharacter]
	Energy=Extreme
	UseRecoilFaktor=Extreme
	FarDistanceAimFOV=Max
	UnityWeaponUnit=Max
	ScopeMoveInOutSpeed=Max
	ScopeAimCrosshairUIScale=90
	ScopeAimShootSpreadDecRotValSpeed=True
	ScopeAimShootSpreadRotValMax=True
	OnCharacterAimModeChanged=True
	CurrentReloadWeapon=High
	AimStateDrawTime=True
	AimStateReturnTime=True
	AimOffsets=Max
	CurInputVector=True
	ScopeNewTargetLoc=True
	IsPeekRight=99
	IsPeekLeft=99
	
[/Script/ShadowTrackerExtra.TargetBodyData]
	t.DamagePosition=9999f
	t.TargetBodyType=999999f
	t.DamageScale=999999f
	
[/Script/ShadowTrackerExtra.STExtraBaseCharacter]
	AimOffsetshell=Max
	CurInputVector=True
	HealthPredict=True
	IsEnablePeek=True
	PeekHashellision=True
	Healerprotect=Max
	ScopeNewTargetLoc=High
	CharacterHead=9.9f
	CharacherBody=3.0f
	CharacterCvars=2.0f
	AnimationKick=9.0f
	AccessoriesRecoveryFactor=6.0f
	AccessoriesHRecoilFactor=6.0f
	AccessoriesVRecoilFactor=6.0f
	AccessoriesDeviationFactor=6.0f
	CrosshairsCursor=true
	DamageRadiusInner=9.9F
	DamageRadiusOuter=9.9F
	CrossHairType=Max
	BulletFireSpeed=High
	ReloadTime=High
	WeaponAimFOV=Max
	ClientHitPartJudgment=1.9
	ClientHitDamage=9f
	ClientBulletFOV=9f
	ClientAimLock=9f
	ClientHitAssist=9f
	ClientDamageHitPart=9f
	ClientHitPartJudgment=9f 

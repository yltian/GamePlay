
set(GAMEPLAY_SRC
    src/AbsoluteLayout.cpp
    src/AbsoluteLayout.h
    src/AIAgent.cpp
    src/AIAgent.h
    src/AIController.cpp
    src/AIController.h
    src/AIMessage.cpp
    src/AIMessage.h
    src/AIState.cpp
    src/AIState.h
    src/AIStateMachine.cpp
    src/AIStateMachine.h
    src/Animation.cpp
    src/Animation.h
    src/AnimationClip.cpp
    src/AnimationClip.h
    src/AnimationController.cpp
    src/AnimationController.h
    src/AnimationTarget.cpp
    src/AnimationTarget.h
    src/AnimationValue.cpp
    src/AnimationValue.h
    src/AudioBuffer.cpp
    src/AudioBuffer.h
    src/AudioController.cpp
    src/AudioController.h
    src/AudioListener.cpp
    src/AudioListener.h
    src/AudioSource.cpp
    src/AudioSource.h
    src/Base.h
    src/BoundingBox.cpp
    src/BoundingBox.h
    src/BoundingBox.inl
    src/BoundingSphere.cpp
    src/BoundingSphere.h
    src/BoundingSphere.inl
    src/Bundle.cpp
    src/Bundle.h
    src/Button.cpp
    src/Button.h
    src/Camera.cpp
    src/Camera.h
    src/CheckBox.cpp
    src/CheckBox.h
    src/Container.cpp
    src/Container.h
    src/Control.cpp
    src/Control.h
    src/ControlFactory.h
    src/ControlFactory.cpp
    src/Curve.cpp
    src/Curve.h
    src/DebugNew.cpp
    src/DebugNew.h
    src/DepthStencilTarget.cpp
    src/DepthStencilTarget.h
    src/Effect.cpp
    src/Effect.h
    src/FileSystem.cpp
    src/FileSystem.h
    src/FlowLayout.cpp
    src/FlowLayout.h
    src/Font.cpp
    src/Font.h
    src/Form.cpp
    src/Form.h
    src/FrameBuffer.cpp
    src/FrameBuffer.h
    src/Frustum.cpp
    src/Frustum.h
    src/Game.cpp
    src/Game.h
    src/Game.inl
    src/Gamepad.cpp
    src/Gamepad.h
    src/gameplay-main-android.cpp
    src/gameplay-main-blackberry.cpp
    src/gameplay-main-linux.cpp
    src/gameplay-main-windows.cpp
    src/Gesture.h
    src/HeightField.cpp
    src/HeightField.h
    src/Image.cpp
    src/Image.h
    src/Image.inl
    src/ImageControl.cpp
    src/ImageControl.h
    src/Joint.cpp
    src/Joint.h
    src/JoystickControl.cpp
    src/JoystickControl.h
    src/Label.cpp
    src/Label.h
    src/Layout.cpp
    src/Layout.h
    src/Light.cpp
    src/Light.h
    src/Logger.cpp
    src/Logger.h
    src/Material.cpp
    src/Material.h
    src/MaterialParameter.cpp
    src/MaterialParameter.h
    src/MathUtil.cpp
    src/MathUtil.h
    src/MathUtil.inl
    src/MathUtilNeon.inl
    src/Matrix.cpp
    src/Matrix.h
    src/Matrix.inl
    src/Mesh.cpp
    src/Mesh.h
    src/MeshBatch.cpp
    src/MeshBatch.h
    src/MeshBatch.inl
    src/MeshPart.cpp
    src/MeshPart.h
    src/MeshSkin.cpp
    src/MeshSkin.h
    src/Model.cpp
    src/Model.h
    src/Node.cpp
    src/Node.h
    src/ParticleEmitter.cpp
    src/ParticleEmitter.h
    src/Pass.cpp
    src/Pass.h
    src/PhysicsCharacter.cpp
    src/PhysicsCharacter.h
    src/PhysicsCollisionObject.cpp
    src/PhysicsCollisionObject.h
    src/PhysicsCollisionShape.cpp
    src/PhysicsCollisionShape.h
    src/PhysicsConstraint.cpp
    src/PhysicsConstraint.h
    src/PhysicsController.cpp
    src/PhysicsController.h
    src/PhysicsFixedConstraint.cpp
    src/PhysicsFixedConstraint.h
    src/PhysicsGenericConstraint.cpp
    src/PhysicsGenericConstraint.h
    src/PhysicsGhostObject.cpp
    src/PhysicsGhostObject.h
    src/PhysicsHingeConstraint.cpp
    src/PhysicsHingeConstraint.h
    src/PhysicsRigidBody.cpp
    src/PhysicsRigidBody.h
    src/PhysicsSocketConstraint.cpp
    src/PhysicsSocketConstraint.h
    src/PhysicsSpringConstraint.cpp
    src/PhysicsSpringConstraint.h
    src/PhysicsVehicle.cpp
    src/PhysicsVehicle.h
    src/PhysicsVehicleWheel.cpp
    src/PhysicsVehicle.h
    src/Plane.cpp
    src/Plane.h
    src/Plane.inl
    src/Platform.h
    src/Platform.cpp
    src/PlatformAndroid.cpp
    src/PlatformBlackBerry.cpp
    src/PlatformLinux.cpp
    src/PlatformWindows.cpp
    src/Properties.cpp
    src/Properties.h
    src/Quaternion.cpp
    src/Quaternion.h
    src/Quaternion.inl
    src/RadioButton.cpp
    src/RadioButton.h
    src/Ray.cpp
    src/Ray.h
    src/Ray.inl
    src/Rectangle.cpp
    src/Rectangle.h
    src/Ref.cpp
    src/Ref.h
    src/RenderState.cpp
    src/RenderState.h
    src/RenderTarget.cpp
    src/RenderTarget.h
    src/Scene.cpp
    src/Scene.h
    src/SceneLoader.cpp
    src/SceneLoader.h
    src/ScreenDisplayer.cpp
    src/ScreenDisplayer.h
    src/ScriptController.cpp
    src/ScriptController.h
    src/ScriptController.inl
    src/ScriptTarget.cpp
    src/ScriptTarget.h
    src/Slider.cpp
    src/Slider.h
    src/SpriteBatch.cpp
    src/SpriteBatch.h
    src/Technique.cpp
    src/Technique.h
    src/Terrain.cpp
    src/Terrain.h
    src/TerrainPatch.cpp
    src/TerrainPatch.h
    src/TextBox.cpp
    src/TextBox.h
    src/Texture.cpp
    src/Texture.h
    src/Theme.cpp
    src/Theme.h
    src/ThemeStyle.cpp
    src/ThemeStyle.h
    src/Transform.cpp
    src/Transform.h
    src/Vector2.cpp
    src/Vector2.h
    src/Vector2.inl
    src/Vector3.cpp
    src/Vector3.h
    src/Vector3.inl
    src/Vector4.cpp
    src/Vector4.h
    src/Vector4.inl
    src/VertexAttributeBinding.cpp
    src/VertexAttributeBinding.h
    src/VertexFormat.cpp
    src/VertexFormat.h
    src/VerticalLayout.cpp
    src/VerticalLayout.h
)

set(GAMEPLAY_LUA
    src/lua/lua_all_bindings.cpp
    src/lua/lua_all_bindings.h
    src/lua/lua_AbsoluteLayout.cpp
    src/lua/lua_AbsoluteLayout.h
    src/lua/lua_AIAgent.cpp
    src/lua/lua_AIAgent.h
    src/lua/lua_AIAgentListener.cpp
    src/lua/lua_AIAgentListener.h
    src/lua/lua_AIController.cpp
    src/lua/lua_AIController.h
    src/lua/lua_AIMessage.cpp
    src/lua/lua_AIMessage.h
    src/lua/lua_AIMessageParameterType.cpp
    src/lua/lua_AIMessageParameterType.h
    src/lua/lua_AIState.cpp
    src/lua/lua_AIState.h
    src/lua/lua_AIStateListener.cpp
    src/lua/lua_AIStateListener.h
    src/lua/lua_AIStateMachine.cpp
    src/lua/lua_AIStateMachine.h
    src/lua/lua_Animation.cpp
    src/lua/lua_Animation.h
    src/lua/lua_AnimationClip.cpp
    src/lua/lua_AnimationClip.h
    src/lua/lua_AnimationClipListener.cpp
    src/lua/lua_AnimationClipListener.h
    src/lua/lua_AnimationClipListenerEventType.cpp
    src/lua/lua_AnimationClipListenerEventType.h
    src/lua/lua_AnimationController.cpp
    src/lua/lua_AnimationController.h
    src/lua/lua_AnimationTarget.cpp
    src/lua/lua_AnimationTarget.h
    src/lua/lua_AnimationValue.cpp
    src/lua/lua_AnimationValue.h
    src/lua/lua_AudioBuffer.cpp
    src/lua/lua_AudioBuffer.h
    src/lua/lua_AudioController.cpp
    src/lua/lua_AudioController.h
    src/lua/lua_AudioListener.cpp
    src/lua/lua_AudioListener.h
    src/lua/lua_AudioSource.cpp
    src/lua/lua_AudioSource.h
    src/lua/lua_AudioSourceState.cpp
    src/lua/lua_AudioSourceState.h
    src/lua/lua_BoundingBox.cpp
    src/lua/lua_BoundingBox.h
    src/lua/lua_BoundingSphere.cpp
    src/lua/lua_BoundingSphere.h
    src/lua/lua_Bundle.cpp
    src/lua/lua_Bundle.h
    src/lua/lua_Button.cpp
    src/lua/lua_Button.h
    src/lua/lua_Camera.cpp
    src/lua/lua_Camera.h
    src/lua/lua_CameraListener.h
    src/lua/lua_CameraListener.cpp
    src/lua/lua_CameraType.cpp
    src/lua/lua_CameraType.h
    src/lua/lua_CheckBox.cpp
    src/lua/lua_CheckBox.h
    src/lua/lua_Container.cpp
    src/lua/lua_Container.h
    src/lua/lua_ContainerScroll.cpp
    src/lua/lua_ContainerScroll.h
    src/lua/lua_Control.cpp
    src/lua/lua_Control.h
    src/lua/lua_ControlAlignment.cpp
    src/lua/lua_ControlAlignment.h
    src/lua/lua_ControlAutoSize.cpp
    src/lua/lua_ControlAutoSize.h
    src/lua/lua_ControlListener.cpp
    src/lua/lua_ControlListener.h
    src/lua/lua_ControlListenerEventType.cpp
    src/lua/lua_ControlListenerEventType.h
    src/lua/lua_ControlState.cpp
    src/lua/lua_ControlState.h
    src/lua/lua_Curve.cpp
    src/lua/lua_Curve.h
    src/lua/lua_CurveInterpolationType.cpp
    src/lua/lua_CurveInterpolationType.h
    src/lua/lua_DepthStencilTarget.cpp
    src/lua/lua_DepthStencilTarget.h
    src/lua/lua_DepthStencilTargetFormat.cpp
    src/lua/lua_DepthStencilTargetFormat.h
    src/lua/lua_Effect.cpp
    src/lua/lua_Effect.h
    src/lua/lua_FileSystem.cpp
    src/lua/lua_FileSystem.h
    src/lua/lua_FlowLayout.cpp
    src/lua/lua_FlowLayout.h
    src/lua/lua_Font.cpp
    src/lua/lua_Font.h
    src/lua/lua_FontFormat.cpp
    src/lua/lua_FontFormat.h
    src/lua/lua_FontJustify.cpp
    src/lua/lua_FontJustify.h
    src/lua/lua_FontStyle.cpp
    src/lua/lua_FontStyle.h
    src/lua/lua_FontText.cpp
    src/lua/lua_FontText.h
    src/lua/lua_Form.cpp
    src/lua/lua_Form.h
    src/lua/lua_FrameBuffer.cpp
    src/lua/lua_FrameBuffer.h
    src/lua/lua_Frustum.cpp
    src/lua/lua_Frustum.h
    src/lua/lua_Game.cpp
    src/lua/lua_Game.h
    src/lua/lua_GameClearFlags.cpp
    src/lua/lua_GameClearFlags.h
    src/lua/lua_Gamepad.cpp
    src/lua/lua_Gamepad.h
    src/lua/lua_GamepadButtonMapping.cpp
    src/lua/lua_GamepadButtonMapping.h
    src/lua/lua_GamepadGamepadEvent.cpp
    src/lua/lua_GamepadGamepadEvent.h
    src/lua/lua_GameState.cpp
    src/lua/lua_GameState.h
    src/lua/lua_Gesture.cpp
    src/lua/lua_Gesture.h
    src/lua/lua_GestureGestureEvent.cpp
    src/lua/lua_GestureGestureEvent.h
    src/lua/lua_Global.cpp
    src/lua/lua_Global.h
    src/lua/lua_HeightField.cpp
    src/lua/lua_HeightField.h
    src/lua/lua_Image.cpp
    src/lua/lua_Image.h
    src/lua/lua_ImageControl.cpp
    src/lua/lua_ImageControl.h
    src/lua/lua_ImageFormat.cpp
    src/lua/lua_ImageFormat.h
    src/lua/lua_Joint.cpp
    src/lua/lua_Joint.h
    src/lua/lua_JoystickControl.cpp
    src/lua/lua_JoystickControl.h
    src/lua/lua_Keyboard.cpp
    src/lua/lua_Keyboard.h
    src/lua/lua_KeyboardKey.cpp
    src/lua/lua_KeyboardKey.h
    src/lua/lua_KeyboardKeyEvent.cpp
    src/lua/lua_KeyboardKeyEvent.h
    src/lua/lua_Label.cpp
    src/lua/lua_Label.h
    src/lua/lua_Layout.cpp
    src/lua/lua_Layout.h
    src/lua/lua_LayoutType.cpp
    src/lua/lua_LayoutType.h
    src/lua/lua_Light.cpp
    src/lua/lua_Light.h
    src/lua/lua_LightType.cpp
    src/lua/lua_LightType.h
    src/lua/lua_Logger.cpp
    src/lua/lua_Logger.h
    src/lua/lua_LoggerLevel.cpp
    src/lua/lua_LoggerLevel.h
    src/lua/lua_Material.cpp
    src/lua/lua_Material.h
    src/lua/lua_MaterialParameter.cpp
    src/lua/lua_MaterialParameter.h
    src/lua/lua_MathUtil.cpp
    src/lua/lua_MathUtil.h
    src/lua/lua_Matrix.cpp
    src/lua/lua_Matrix.h
    src/lua/lua_Mesh.cpp
    src/lua/lua_Mesh.h
    src/lua/lua_MeshBatch.cpp
    src/lua/lua_MeshBatch.h
    src/lua/lua_MeshIndexFormat.cpp
    src/lua/lua_MeshIndexFormat.h
    src/lua/lua_MeshPart.cpp
    src/lua/lua_MeshPart.h
    src/lua/lua_MeshPrimitiveType.cpp
    src/lua/lua_MeshPrimitiveType.h
    src/lua/lua_MeshSkin.cpp
    src/lua/lua_MeshSkin.h
    src/lua/lua_Model.cpp
    src/lua/lua_Model.h
    src/lua/lua_Mouse.cpp
    src/lua/lua_Mouse.h
    src/lua/lua_MouseMouseEvent.cpp
    src/lua/lua_MouseMouseEvent.h
    src/lua/lua_Node.cpp
    src/lua/lua_Node.h
    src/lua/lua_NodeCloneContext.cpp
    src/lua/lua_NodeCloneContext.h
    src/lua/lua_NodeType.cpp
    src/lua/lua_NodeType.h
    src/lua/lua_ParticleEmitter.cpp
    src/lua/lua_ParticleEmitter.h
    src/lua/lua_ParticleEmitterTextureBlending.cpp
    src/lua/lua_ParticleEmitterTextureBlending.h
    src/lua/lua_Pass.cpp
    src/lua/lua_Pass.h
    src/lua/lua_PhysicsCharacter.cpp
    src/lua/lua_PhysicsCharacter.h
    src/lua/lua_PhysicsCollisionObject.cpp
    src/lua/lua_PhysicsCollisionObject.h
    src/lua/lua_PhysicsCollisionObjectCollisionListener.cpp
    src/lua/lua_PhysicsCollisionObjectCollisionListener.h
    src/lua/lua_PhysicsCollisionObjectCollisionListenerEventType.cpp
    src/lua/lua_PhysicsCollisionObjectCollisionListenerEventType.h
    src/lua/lua_PhysicsCollisionObjectCollisionPair.cpp
    src/lua/lua_PhysicsCollisionObjectCollisionPair.h
    src/lua/lua_PhysicsCollisionObjectType.cpp
    src/lua/lua_PhysicsCollisionObjectType.h
    src/lua/lua_PhysicsCollisionShape.cpp
    src/lua/lua_PhysicsCollisionShape.h
    src/lua/lua_PhysicsCollisionShapeDefinition.cpp
    src/lua/lua_PhysicsCollisionShapeDefinition.h
    src/lua/lua_PhysicsCollisionShapeType.cpp
    src/lua/lua_PhysicsCollisionShapeType.h
    src/lua/lua_PhysicsConstraint.cpp
    src/lua/lua_PhysicsConstraint.h
    src/lua/lua_PhysicsController.cpp
    src/lua/lua_PhysicsController.h
    src/lua/lua_PhysicsControllerHitFilter.cpp
    src/lua/lua_PhysicsControllerHitFilter.h
    src/lua/lua_PhysicsControllerHitResult.cpp
    src/lua/lua_PhysicsControllerHitResult.h
    src/lua/lua_PhysicsControllerListener.cpp
    src/lua/lua_PhysicsControllerListener.h
    src/lua/lua_PhysicsControllerListenerEventType.cpp
    src/lua/lua_PhysicsControllerListenerEventType.h
    src/lua/lua_PhysicsFixedConstraint.cpp
    src/lua/lua_PhysicsFixedConstraint.h
    src/lua/lua_PhysicsGenericConstraint.cpp
    src/lua/lua_PhysicsGenericConstraint.h
    src/lua/lua_PhysicsGhostObject.cpp
    src/lua/lua_PhysicsGhostObject.h
    src/lua/lua_PhysicsHingeConstraint.cpp
    src/lua/lua_PhysicsHingeConstraint.h
    src/lua/lua_PhysicsRigidBody.cpp
    src/lua/lua_PhysicsRigidBody.h
    src/lua/lua_PhysicsRigidBodyParameters.cpp
    src/lua/lua_PhysicsRigidBodyParameters.h
    src/lua/lua_PhysicsSocketConstraint.cpp
    src/lua/lua_PhysicsSocketConstraint.h
    src/lua/lua_PhysicsSpringConstraint.cpp
    src/lua/lua_PhysicsSpringConstraint.h
    src/lua/lua_PhysicsVehicle.cpp
    src/lua/lua_PhysicsVehicle.h
    src/lua/lua_PhysicsVehicleWheel.cpp
    src/lua/lua_PhysicsVehicleWheel.h
    src/lua/lua_Plane.cpp
    src/lua/lua_Plane.h
    src/lua/lua_Platform.cpp
    src/lua/lua_Platform.h
    src/lua/lua_Properties.cpp
    src/lua/lua_Properties.h
    src/lua/lua_PropertiesType.cpp
    src/lua/lua_PropertiesType.h
    src/lua/lua_Quaternion.cpp
    src/lua/lua_Quaternion.h
    src/lua/lua_RadioButton.cpp
    src/lua/lua_RadioButton.h
    src/lua/lua_Ray.cpp
    src/lua/lua_Ray.h
    src/lua/lua_Rectangle.cpp
    src/lua/lua_Rectangle.h
    src/lua/lua_Ref.cpp
    src/lua/lua_Ref.h
    src/lua/lua_RenderState.cpp
    src/lua/lua_RenderState.h
    src/lua/lua_RenderStateAutoBinding.cpp
    src/lua/lua_RenderStateAutoBinding.h
    src/lua/lua_RenderStateBlend.cpp
    src/lua/lua_RenderStateBlend.h
    src/lua/lua_RenderStateCullFaceSide.cpp
    src/lua/lua_RenderStateDepthFunction.cpp
    src/lua/lua_RenderStateDepthFunction.h
    src/lua/lua_RenderStateFrontFace.cpp
    src/lua/lua_RenderStateFrontFace.h
    src/lua/lua_RenderStateStateBlock.cpp
    src/lua/lua_RenderStateStateBlock.h
    src/lua/lua_RenderStateStencilFunction.cpp
    src/lua/lua_RenderStateStencilFunction.h
    src/lua/lua_RenderStateStencilOperation.cpp
    src/lua/lua_RenderStateStencilOperation.h
    src/lua/lua_RenderTarget.cpp
    src/lua/lua_RenderTarget.h
    src/lua/lua_Scene.cpp
    src/lua/lua_Scene.h
    src/lua/lua_ScreenDisplayer.cpp
    src/lua/lua_ScreenDisplayer.h
    src/lua/lua_ScriptController.cpp
    src/lua/lua_ScriptController.h
    src/lua/lua_ScriptTarget.cpp
    src/lua/lua_ScriptTarget.h
    src/lua/lua_Slider.cpp
    src/lua/lua_Slider.h
    src/lua/lua_SpriteBatch.cpp
    src/lua/lua_SpriteBatch.h
    src/lua/lua_Technique.cpp
    src/lua/lua_Technique.h
    src/lua/lua_Terrain.cpp
    src/lua/lua_Terrain.h
    src/lua/lua_TerrainFlags.cpp
    src/lua/lua_TerrainFlags.h
    src/lua/lua_TerrainPatch.cpp
    src/lua/lua_TerrainPatch.h
    src/lua/lua_TextBox.cpp
    src/lua/lua_TextBox.h
    src/lua/lua_TextBoxInputMode.cpp
    src/lua/lua_TextBoxInputMode.h
    src/lua/lua_Texture.cpp
    src/lua/lua_Texture.h
    src/lua/lua_TextureFilter.cpp
    src/lua/lua_TextureFilter.h
    src/lua/lua_TextureFormat.cpp
    src/lua/lua_TextureFormat.h
    src/lua/lua_TextureSampler.cpp
    src/lua/lua_TextureSampler.h
    src/lua/lua_TextureWrap.cpp
    src/lua/lua_TextureWrap.h
    src/lua/lua_Theme.cpp
    src/lua/lua_Theme.h
    src/lua/lua_ThemeSideRegions.cpp
    src/lua/lua_ThemeSideRegions.h
    src/lua/lua_ThemeStyle.cpp
    src/lua/lua_ThemeStyle.h
    src/lua/lua_ThemeThemeImage.cpp
    src/lua/lua_ThemeThemeImage.h
    src/lua/lua_ThemeUVs.cpp
    src/lua/lua_ThemeUVs.h
    src/lua/lua_Touch.cpp
    src/lua/lua_Touch.h
    src/lua/lua_TouchTouchEvent.cpp
    src/lua/lua_TouchTouchEvent.h
    src/lua/lua_Transform.cpp
    src/lua/lua_Transform.h
    src/lua/lua_TransformListener.cpp
    src/lua/lua_TransformListener.h
    src/lua/lua_Uniform.cpp
    src/lua/lua_Uniform.h
    src/lua/lua_Vector2.cpp
    src/lua/lua_Vector2.h
    src/lua/lua_Vector3.cpp
    src/lua/lua_Vector3.h
    src/lua/lua_Vector4.cpp
    src/lua/lua_Vector4.h
    src/lua/lua_VertexAttributeBinding.cpp
    src/lua/lua_VertexAttributeBinding.h
    src/lua/lua_VertexFormat.cpp
    src/lua/lua_VertexFormat.h
    src/lua/lua_VertexFormatElement.cpp
    src/lua/lua_VertexFormatElement.h
    src/lua/lua_VertexFormatUsage.cpp
    src/lua/lua_VertexFormatUsage.h
    src/lua/lua_VerticalLayout.cpp
    src/lua/lua_VerticalLayout.h
)

set(GAMEPLAY_RES
    res/logo_black.png
    res/logo_powered_black.png
    res/logo_powered_white.png
    res/logo_white.png
)

set(GAMEPLAY_RES_SHADERS
    res/shaders/colored.frag
    res/shaders/colored.vert
    res/shaders/font.frag
    res/shaders/font.vert
    res/shaders/form.frag
    res/shaders/form.vert
    res/shaders/lighting.frag
    res/shaders/lighting.vert
    res/shaders/skinning.vert
    res/shaders/skinning-none.vert
    res/shaders/sprite.frag
    res/shaders/sprite.vert
    res/shaders/terrain.frag
    res/shaders/terrain.vert
    res/shaders/textured.frag
    res/shaders/textured.vert
)

set(GAMEPLAY_RES_SHADERS
    res/ui/arial.gpb
    res/ui/default.png
    res/ui/default.theme
)

include_directories( 
    src
    ../external-deps/lua/include
    ../external-deps/bullet/include
    ../external-deps/png/include
    ../external-deps/zlib/include
    ../external-deps/oggvorbis/include
    ../external-deps/openal/include
    ../external-deps/glew/include
)

IF(CMAKE_SYSTEM_NAME MATCHES "Linux")
find_package(PkgConfig REQUIRED)
pkg_check_modules(GTK2 REQUIRED gtk+-2.0)
include_directories(${GTK2_INCLUDE_DIRS})
add_definitions(${GTK2_CFLAGS_OTHER})
add_definitions(-D__linux__)
ENDIF(CMAKE_SYSTEM_NAME MATCHES "Linux")

add_definitions(-lstdc++)

add_library(gameplay STATIC
    ${GAMEPLAY_SRC}
    ${GAMEPLAY_LUA}
)

set_target_properties(gameplay PROPERTIES
    OUTPUT_NAME "gameplay"
    CLEAN_DIRECT_OUTPUT 1
    VERSION ${GAMEPLAY_VERSION}
)

source_group(lua FILES ${GAMEPLAY_LUA})
source_group(res FILES ${GAMEPLAY_RES} ${GAMEPLAY_RES} ${GAMEPLAY_RES_SHADERS} ${GAMEPLAY_RES_UI})
source_group(src FILES ${GAMEPLAY_SRC})




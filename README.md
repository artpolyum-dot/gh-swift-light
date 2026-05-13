Version: 1.0.0

Light placement in Cinema 4D is no longer a tedious chore. GH Swift Light introduces a raycasting-based, intuitive click-and-drag placement system along with an integrated control suite.
(Cinema 4D에서 라이트 배치는 더 이상 번거로운 작업이 아닙니다. GH Swift Light는 레이캐스팅 기반의 직관적인 클릭-드래그 배치와 통합 제어 시스템을 추가합니다.)



Not only does it allow for sophisticated lighting that follows surfaces with precision, but it also enables you to intuitively manage core attributes—such as intensity, visibility, and color—all at once through the Place Tool’s Attribute window, hotkeys, and the Light Mixer.
(표면을 따라 움직이는 정교한 라이팅은 물론, 광량과 가시성, 컬러 같은 핵심 속성을 Place Tool의 Attribute 창, 단축키, Light Mixer에서 한 번에 직관적으로 해결할 수 있게 도와줍니다.)

Compatible with Cinema 4D 2025 (Standard, Redshift, Octane)
(Cinema 4D 2025 호환: 스탠다드, 레드시프트, 옥테인 지원)




Core Workflow (핵심 사용 흐름)

Launch Light Place tool in Cinema 4D.
(Cinema 4D에서 Light Place tool 툴을 실행합니다.)



Select the light you wish to adjust.
(조절할 라이트를 선택합니다.)



Choose a placement mode from the Operation Mode options.
(Operation Mode에서 배치 방식을 고릅니다.)



Click or drag on the viewport surface to position the light.
(뷰포트 표면을 클릭하거나 드래그해서 라이트를 배치합니다.)



Adjust Distance, Size, and Intensity via Tool Attributes or hotkey-drags.
(Distance, Size, Intensity를 Tool Attribute 또는 단축키 드래그로 조절합니다.)



Manage multiple lights simultaneously using the Light Mixer or Light List.
(여러 라이트는 Light Mixer, Light List에서 한 번에 관리합니다.)

Placement Modes (배치 모드)

Direct
<img width="1908" height="678" alt="image" src="https://github.com/user-attachments/assets/409d7945-ba84-4bbb-9a41-dd09d006ac71" />
Clicking a surface places the light so it points directly at that spot. This is the most fundamental placement method.
(표면을 클릭하면 라이트가 그 지점을 향하도록 배치됩니다. 가장 기본적인 라이트 배치 방식입니다.)





The light moves based on the surface position.
(표면 위치를 기준으로 라이트가 이동합니다.)



It is positioned away from the surface by the designated Distance value.
(Distance 값만큼 표면에서 떨어진 위치에 배치됩니다.)



Enabling "Keep Upright (Fixed Horizon)" prevents unnecessary tilting or rotation, maintaining a stable horizon.
(Keep Upright (Fixed Horizon)을 켜면 라이트가 불필요하게 기울어지거나 회전하는 것을 줄이고 수평감을 유지합니다.)



Supports both click and drag placement.
(클릭 배치와 드래그 배치를 모두 지원합니다.)

Reflect



This mode positions the light near the reflection vector relative to the surface.
(표면을 기준으로 반사 방향에 가까운 라이트 위치를 잡는 모드입니다.)





Calculates the light direction based on the surface normal and the current light/camera relationship.
(표면의 방향과 현재 라이트/카메라 관계를 기준으로 라이트 방향을 계산합니다.)



Useful for product lighting, adjusting highlights, and finding reflection points.
(제품 조명, 하이라이트 조정, 반사 위치 잡기에 유용합니다.)



Fine-tune the reflection position horizontally or vertically using Offset values.
(Offset Horizontal, Offset Vertical 값으로 반사 기준에서 좌우/상하 방향을 미세 조절할 수 있습니다.)



"Smoothness" ensures fluid movement during dragging.
(Smoothness와 함께 사용하면 드래그 중 움직임이 부드럽게 이어집니다.)

Radial



Positions the light in a circular orbit around a specific surface point.
(표면 지점을 중심으로 라이트를 원형 궤도처럼 배치하는 모드입니다.)





The light moves along the circumference centered on the selected point.
(선택한 표면 지점을 기준으로 라이트가 둘레 방향으로 움직입니다.)



Ideal for wrapping light around characters, products, or objects.
(캐릭터, 제품, 오브젝트 주변에 조명을 감싸듯 배치할 때 유용합니다.)



Adjust wrapping angles and tilt feel with "Radial Tilt (Wrap)".
(Radial Tilt (Wrap)으로 감기는 각도와 기울기 느낌을 조절합니다.)

Orbit



Moves the light in a rotation around a defined pivot.
(라이트가 피벗을 중심으로 회전하도록 움직이는 모드입니다.)





Rotates the light while maintaining its distance from the pivot.
(라이트와 피벗 사이 거리를 유지하면서 라이트를 돌립니다.)



The "Ctrl+Drag Action" allows you to choose between Intensity or Pivot Position.
(Ctrl+Drag Action에서 Intensity 또는 Pivot Position을 선택할 수 있습니다.)



Selecting "Pivot Position" lets you redefine the orbit center via Ctrl+Drag.
(Pivot Position을 선택하면 Ctrl 드래그로 오비트 중심점을 다시 잡을 수 있습니다.)

Place



Focuses on positioning rather than orientation.
(라이트의 방향보다는 위치 배치에 집중하는 모드입니다.)





Designed for quickly dropping lights onto specific surface spots.
(표면 위 특정 지점에 라이트를 빠르게 놓는 용도입니다.)



Use this to move lights to specific locations without altering their rotation.
(라이트를 특정 위치에 각도 변화 없이 고정적으로 옮기고 싶을 때 사용합니다.)

Rotate




Adjusts the direction of the selected light through dragging.
(선택한 라이트의 방향을 드래그로 조절하는 모드입니다.)





Performs rotation adjustments without the need for surface picking.
(표면 피킹 없이 라이트 회전 조절을 수행합니다.)

Interaction Style (상호작용 스타일)

Raycast (Jump)



Instantly repositions the light to the surface point under the mouse cursor.
(마우스가 가리키는 표면을 바로 다시 찍어서 라이트를 이동시키는 기본 방식입니다.)





The light jumps to the point as soon as you click.
(클릭하면 해당 표면 지점으로 즉시 배치됩니다.)



Suitable for rapidly placing lights across multiple surfaces.
(빠르게 여러 표면에 라이트를 배치할 때 적합합니다.)

Slide (Relative)



Moves the light smoothly based on the initial surface point picked.
(처음 잡은 표면을 기준으로 미끄러지듯 움직이는 방식입니다.)





The movement follows the trajectory starting from the initial drag point.
(드래그 시작 지점을 기준으로 움직임을 이어갑니다.)



Designed to follow the visible surface without jumping to hidden geometry behind edges.
(표면 가장자리에서는 보이는 표면 기준으로 이동하며, 가려진 깊은 표면을 임의로 따라가지 않도록 설계되어 있습니다.)

Hidden Target Placement (숨겨진 타겟 배치)





When "Allow Hidden Target" is enabled, lights can be placed on hidden targets.
(Allow Hidden Target이 켜져 있으면 숨겨진 타겟에도 배치할 수 있습니다.)



Supports surface interpretation for caches, deformers, instances, and cloners where possible.
(캐시, 디포머, 인스턴스, 클로너 계열의 표면도 가능한 범위에서 해석합니다.)



Uses specialized picking logic since hidden targets are invisible in the viewport.
(숨겨진 타겟은 뷰포트에서 보이지 않기 때문에 별도 피킹 로직을 사용합니다.)



Utilizes a C++ companion for fast, exact picking; falls back to Python if unavailable.
(C++ companion이 사용 가능하면 더 빠른 exact pick을 사용하고, 실패하거나 없으면 Python fallback으로 동작합니다.)

Hidden Outline (숨겨진 외곽선)



Displays hidden targets as guides to assist the user.
(숨겨진 타겟을 작업자가 볼 수 있도록 가이드 형태로 표시하는 기능입니다.)
Enables lightweight and fast placement even on complex, high-polygon objects.
(폴리곤이 많고 복잡한 오브젝트의 경우 이 기능을 사용해서 가볍고 빠르게 라이트 배치가 가능해집니다.)





Shows wire outlines and can display faces in "Polygon Overlay" mode.
(숨겨진 타겟의 wire outline을 표시하며, polygon overlay 모드에서 면 형태로도 확인할 수 있습니다.)



Customizable opacity, color, and X-Ray options for clearer structural visibility.
(Outline Opacity, Color, X-Ray 옵션으로 투명도와 색상을 바꾸거나 가려진 구조를 쉽게 확인할 수 있습니다.)

Guide Line (가이드라인)

Visualizes the relationship between the light and its placement point.
(Guide line은 선택한 라이트와 배치 지점 사이의 관계를 뷰포트에서 보여주는 시각 보조 기능입니다.)





Distinct colors can be set for selected vs. unselected light guides.
(선택 라이트와 선택하지 않은 라이트의 guide line 색을 따로 설정할 수 있습니다.)

Viewport Selection (뷰포트 선택)

"Enable Viewport Selection (Light Click)" allows direct selection of lights in the viewport.
(Enable Viewport Selection (Light Click)은 뷰포트에서 라이트를 직접 클릭해 선택할 수 있게 하는 옵션입니다.)

Light Property Adjustments (라이트 속성 조절)



Core attributes of the selected light can be managed directly within the Tool Attributes.
(선택한 라이트의 주요 속성은 Tool Attribute 안에서 바로 조절할 수 있습니다.)





Distance: Distance between the pivot (surface) and the light. (피벗과 라이트 거리)



Intensity/Exposure: Adjust brightness or power, including Redshift-specific Exposure. (밝기, 파워 및 레드시프트 노출 조절)



Size/Scale: Control dimensions of area lights or renderer-specific size parameters. (광원 크기 및 스케일 조절)



Renderer Specifics: Automatically maps to Redshift (Cone/Falloff Angle) and Octane (Power/Size) parameters. 
(레드시프트의 Cone Angle이나 옥테인의 Power 등 렌더러별 파라미터 자동 연결)

Drag-Style Shortcuts (드래그 스타일 단축키)



You can instantly edit light values by dragging the mouse while holding down the shortcut key.
단축키와 함께 마우스를 드래그하면서 라이트 값을 즉시 편집할 수 있습니다.)





Ctrl + Drag: Adjust Intensity (기본 Ctrl: Intensity 조절)



Shift + Drag: Adjust Size (기본 Shift: Size 조절)



Ctrl + Shift + Drag: Adjust Distance (기본 Ctrl+Shift: Distance 조절)



Settings에서 각 단축키 조합을 다시 지정할 수 있습니다.



Sensitivity settings are available for Distance, Size, and Intensity. (조절 속도 감도 설정 가능)

Pie Menu



The Pie Menu is a popup menu that allows you to quickly change the placement mode at your mouse position.
(Pie Menu는 마우스 위치에서 배치 모드를 빠르게 변경할 수 있는 팝업 메뉴입니다.)





The default activation key is Q.
(기본 활성 키는 Q입니다.)



You can choose between Q, V, Space, Tab, or in the Settings. 
(Settings에서 Q, V, Space, Tab, 중 선택할 수 있습니다.)



The menu displays Direct, Reflect, Radial, Orbit, Place, and Rotate.
(메뉴에는 Direct, Reflect, Radial, Orbit, Place, Rotate가 표시됩니다.)



After selection, it immediately returns to the GH Swift Light Tool.
(선택 후 즉시 GH Swift Light Tool로 돌아옵니다.)






Light Mixer

A card-based interface for managing all lights in the scene.
(씬 안의 라이트를 카드 형태로 모아 조정하는 패널입니다.)





Displays renderer type, light icons, and allows for quick Intensity, Exposure, and Color adjustments.
(렌더러 이름, 아이콘 표시 및 밝기, 노출, 색상 스와치를 직접 조절할 수 있습니다.)



Features Solo/Enable toggles and Layer Filter support.
(Solo/Enable 토글과 레이어 필터 기능을 지원합니다.)

Light List

A list-view manager that synchronizes selection states and allows batch toggling of visibility.
(라이트를 리스트 형태로 관리하며, 선택 상태 동기화 및 가시성을 빠르게 토글할 수 있는 창입니다.)


Solo 기능

Isolates specific light types (Area, Spot, Dome, etc.) to check their individual impact.
(원하는 라이트만 남기고 나머지 라이트를 꺼서 조명 영향을 빠르게 확인하는 기능입니다.)

카메라 토글

"Selected Object as Camera Toggle" switches the viewport view to the selected object or back to the editor camera. 
(선택한 오브젝트를 현재 뷰포트 카메라로 전환하거나 기본 에디터 카메라로 되돌리는 명령입니다.)


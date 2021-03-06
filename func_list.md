SD Function | Name And Signature
--- | --- 
**Degrees to Radians**|`deg_to_rad(deg: float)`
**asin**|`asin(x: float)`
**acos**|`acos(x: float)`
**Even Count**|`evencount(Input: float)`
**OddCount**|`oddcount(Input: float)`
**ParityTest**|`paritytest(Input: float)`
**Ln**|`ln(a: float)`
**Pi**|`pi()`
**2 Pi**|`_2pi()`
**Pow**|`pow(x: float, n: float)`
**Roughness**|`roughness(Roughness: float, CurrentLevel: int, TotalLevel: int, GlobalOpacity: float)`
**Equality (float2)**|`equality_float2(A: float2, B: float2)`
**Equality (float3)**|`equality_float3(A: float3, B: float3)`
**Equality (boolean)**|`equality_boolean(A: bool, B: bool)`
**Equality (float4)**|`equality_float4(A: float4, B: float4)`
**Not Equal (float2)**|`notequal_float2(A: float2, B: float2)`
**Not Equal (float3)**|`notequal_float3(A: float3, B: float3)`
**Not Equal (float4)**|`notequal_float4(A: float4, B: float4)`
**Not Equal (boolean)**|`notequal_boolean(A: bool, B: bool)`
**Curve**|`curve_function(curve: float, input: float)`
**Merge (float4)**|`merge_float4(x: float, y: float, z: float, w: float)`
**Merge (float3)**|`merge_float3(x: float, y: float, z: float)`
**Distance (float3)**|`distance_vec3(a: float3, b: float3)`
**Distance (float2)**|`distance_vec2(a: float2, b: float2)`
**Length (float2)**|`length_vec2(v: float2)`
**Length (float3)**|`length_vec3(v: float3)`
**Sign**|`sign(x: float)`
**Reflect**|`reflect(i: float3, n: float3)`
**One minus**|`oneminus(x: float)`
**Fmod**|`fmod(a: float, b: float)`
**Frac**|`frac(input: float)`
**Cross product**|`cross_product(a: float3, b: float3)`
**Step**|`step(a: float, x: float)`
**Scalar division (float4)**|`divide_float4(input: float4, scalar: float)`
**Scalar division (float3)**|`divide_float3(input: float3, scalar: float)`
**Scalar division (float2)**|`divide_float2(input: float2, scalar: float)`
**Clamp**|`clamp(input: float, min: float, max: float)`
**Normalize Vec2**|`normalize_vec2(input: float2)`
**Normalize Vec3**|`normalize_vec3(input: float3)`
**Normalize Vec4**|`normalize_vec4(input: float4)`
**Smoothstep**|`smoothstep(a: float, b: float, x: float)`
**Saturate float2**|`saturate_float2(input: float2)`
**Saturate**|`saturate(input: float)`
**Random Uniform [A, B[**|`uniform_ab(A: float, B: float)`
**Random Discrete [A, B]**|`discrete_ab(A: float, B: float, Probability: float)`
**Random Uniform [-1, 1[**|`uniform_11()`
**Random Uniform Float2 [A,B[**|`uniform_f2_ab(A2: float2, B2: float2)`
**Random Uniform Float3 [A,B[**|`uniform_f3_ab(A: float3, B: float3)`
**Random Uniform Float4 [A, B[**|`uniform_f4_ab(A: float4, B: float4)`
**Degrees to Turns**|`degrees_to_turn(input: float)`
**Global Random**|`globalrandom(Input: float, Seed: int)`
**Normal Distribution**|`normal_distribution(radius: float, uniform_random: float2)`
**Directional Offset**|`directional_offset(Direction: float, Distance: float)`
**Matrix Multiply**|`matrixmultiply(MatrixA: float4, MatrixB: float4)`
**Rotation Matrix**|`rotationmatrix(RotationW: float)`
**Scale Matrix**|`scalematrix(ScaleUV: float2)`
**Tile Matrix**|`tilematrix(tiles_xy: float2)`
**Rotate Vec2**|`rotate_vec2(vec2: float2, angle: float, pivot: float2)`
**Wave**|`wave(Amplitude: float, Frequency: float, greaterThanZero: bool)`
**[-1, 1] to [0,1]**|`_1_1_to_0_1(Input: float)`
**[0, 1] to [-1, 1]**|`_0_1_to_1_1(Input: float)`
**[0, 1] to [1, 0]**|`_0_1_to_1_0(Input: float)`
**Negate Float1**|`negatefloat(Input: float)`
**Height Balance**|`height_balance_fn(Depth_Balance: float)`
**Boolean to Float1**|`booleantofloat1(Boolean: bool)`
**Turns to Degrees**|`turnstodegrees(turns: float)`
**Direction To Normal**|`directiontonormal(Direction: float, slopeAngle: float, yUp: bool)`
**RGB to HSL**|`rgbtohsl(RGB: float3)`
**HSL to RGB**|`hsltorgb(HSL: float3)`
**Random Color**|`random_color(RGB: float3, RGB_Randomness: float3)`
**Random Luminosity**|`random_luminosity(RGB: float3, Luminosity_Randomness: float)`
**RGB to HSV**|`rgbtohsv(rgb: float3)`
**RGB to HSI**|`rgbtohsi(rgb: float3)`
**RGB to HCL**|`rgbtohcl(rgb: float3)`
**RGB Lightness Average**|`rgb_lightness_average(rgb: float3)`
**RGB Lightness Hexcone**|`rgb_lightness_hexcone(rgb: float3)`
**RGB Lightness Bi-Hexcone**|`rgb_lightness_bihexcone(rgb: float3)`
**RGB Lightness Luma Rec. 601**|`rgb_lightness_luma_rec601(rgb: float3)`
**RGB Lightness Luma Rec. 709**|`rgb_lightness_luma_rec709(rgb: float3)`
**RGB Chroma Hexagonal**|`rgb_chroma_hexagonal(rgb: float3)`
**RGB Chroma 2 Polar**|`rgb_chroma_2_polar(rgb: float3)`
**RGB Hue Hexagonal**|`rgb_hue_hexagonal(rgb: float3)`
**RGB Hue 2 Polar**|`rgb_hue_2_polar(rgb: float3)`
**RGB Saturation HSV**|`rgb_saturation_hsv(rgb: float3)`
**RGB Saturation HSL**|`rgb_saturation_hsl(rgb: float3)`
**RGB Saturation HSI**|`rgb_saturation_hsi(rgb: float3)`
**HSI to RGB**|`hsitorgb(hsi: float3)`
**HSV to RGB**|`hsvtorgb(hsv: float3)`
**HCL to RGB**|`hcltorgb(hcl: float3)`
**Linear to sRGB (luminance)**|`linear_to_srgb_luminance(input: float)`
**Linear to sRGB**|`linear_to_srgb_rgb(input: float3)`
**sRGB to Linear**|`srgb_to_linear_rgb(input: float3)`
**sRGB to Linear (luminance)**|`srgb_to_linear_luminance(input: float)`
**Temprature to RGB**|`temperature_to_rgb(temperature: float)`
**Temprature to RGB Fit**|`temperature_to_rgb_fit(input: float, a: float, b: float, c: float, d: float)`
**ACEScg to Linear sRGB**|`acescg_to_linear_srgb(input: float3)`
**Linear sRGB to ACEScg**|`linear_srgb_to_acescg(input: float3)`
**disorder**|`disorder(disorder_radius: float, disorder_angle: float)`
**Non Square Output Size**|`non_square_output_size(scale: int, output_size: int2, non_square: bool)`
**Non Square Expansion UV Scale**|`non_square_expansion_uv_scale(position: float2, non_square_expansion: bool)`
**Switch Float1 2 Inputs**|`switch_float1_2_inputs(input_selection: int, value_1: float, value_2: float)`
**Switch Float1 4 Inputs**|`switch_float1_4_inputs(input_selection: int, value_1: float, value_2: float, value_3: float, value_4: float)`
**Switch Float1 8 Inputs**|`switch_float1_8_inputs(input_selection: int, value_1: float, value_2: float, value_3: float, value_4: float, value_5: float, value_6: float, value_7: float, value_8: float)`
**Switch Float2 2 Inputs**|`switch_float2_2_inputs(input_selection: int, value_1: float2, value_2: float2)`
**Switch Float2 4 Inputs**|`switch_float2_4_inputs(input_selection: int, value_1: float2, value_2: float2, value_3: float2, value_4: float2)`
**Switch Float2 8 Inputs**|`switch_float2_8_inputs(input_selection: int, value_1: float2, value_2: float2, value_3: float2, value_4: float2, value_5: float2, value_6: float2, value_7: float2, value_8: float2)`
**Switch Float3 2 Inputs**|`switch_float3_2_inputs(input_selection: int, value_1: float3, value_2: float3)`
**Switch Float3 4 Inputs**|`switch_float3_4_inputs(input_selection: int, value_1: float3, value_2: float3, value_3: float3, value_4: float3)`
**Switch Float3 8 Inputs**|`switch_float3_8_inputs(input_selection: int, value_1: float3, value_2: float3, value_3: float3, value_4: float3, value_5: float3, value_6: float3, value_7: float3, value_8: float3)`
**Switch Float4 2 Inputs**|`switch_float4_2_inputs(input_selection: int, value_1: float4, value_2: float4)`
**Switch Float4 4 Inputs**|`switch_float4_4_inputs(input_selection: int, value_1: float4, value_2: float4, value_3: float4, value_4: float4)`
**Switch Float4 8 Inputs**|`switch_float4_8_inputs(input_selection: int, value_1: float4, value_2: float4, value_3: float4, value_4: float4, value_5: float4, value_6: float4, value_7: float4, value_8: float4)`
**Switch Integer1 2 Inputs**|`switch_integer1_2_inputs(input_selection: int, value_1: int, value_2: int)`
**Switch Integer1 4 Inputs**|`switch_integer1_4_inputs(input_selection: int, value_1: int, value_2: int, value_3: int, value_4: int)`
**Switch Integer1 8 Inputs**|`switch_integer1_8_inputs(input_selection: int, value_1: int, value_2: int, value_3: int, value_4: int, value_5: int, value_6: int, value_7: int, value_8: int)`
**Switch Integer2 2 Inputs**|`switch_integer2_2_inputs(input_selection: int, value_1: int2, value_2: int2)`
**Switch Integer2 4 Inputs**|`switch_integer2_4_inputs(input_selection: int, value_1: int2, value_2: int2, value_3: int2, value_4: int2)`
**Switch Integer2 8 Inputs**|`switch_integer2_8_inputs(input_selection: int, value_1: int2, value_2: int2, value_3: int2, value_4: int2, value_5: int2, value_6: int2, value_7: int2, value_8: int2)`
**Switch Integer3 2 Inputs**|`switch_integer3_2_inputs(input_selection: int, value_1: int3, value_2: int3)`
**Switch Integer3 2 Inputs**|`switch_integer3_4_inputs(input_selection: int, value_1: int3, value_2: int3, value_3: int3, value_4: int3)`
**Switch Integer3 2 Inputs**|`switch_integer3_8_inputs(input_selection: int, value_1: int3, value_2: int3, value_3: int3, value_4: int3, value_5: int3, value_6: int3, value_7: int3, value_8: int3)`
**Switch Integer4 2 Inputs**|`switch_integer4_2_inputs(input_selection: int, value_1: int4, value_2: int4)`
**Switch Integer4 4 Inputs**|`switch_integer4_4_inputs(input_selection: int, value_1: int4, value_2: int4, value_3: int4, value_4: int4)`
**Switch Integer4 8 Inputs**|`switch_integer4_8_inputs(input_selection: int, value_1: int4, value_2: int4, value_3: int4, value_4: int4, value_5: int4, value_6: int4, value_7: int4, value_8: int4)`

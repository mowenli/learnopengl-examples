fips_begin_app(1-5-1-in-out windowed)
    fips_vs_warning_level(3)
    fips_files(1-in-out.c)
    sokol_shader(1-in-out.glsl ${slang})
    fips_deps(sokol)
fips_end_app()

fips_begin_app(1-5-2-uniforms windowed)
    fips_vs_warning_level(3)
    fips_files(2-uniforms.c)
    sokol_shader(2-uniforms.glsl ${slang})
    fips_deps(sokol)
fips_end_app()

fips_begin_app(1-5-3-attributes windowed)
    fips_vs_warning_level(3)
    fips_files(3-attributes)
    sokol_shader(3-attributes.glsl ${slang})
    fips_deps(sokol)
fips_end_app()

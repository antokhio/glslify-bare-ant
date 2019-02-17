# glslify-bare-ant
glslify browserify transform with extra extensions, to compile glsl shaders using require.

ripped from https://github.com/jnordberg/glslify-bare

usage 
{
  "scripts": {
    "build": "browserify app.js -t glslify -t glslify-bare-ant -o public/bundle.js"
    }
}
    
takes .glsl, .vert, .frag extensions

allows:

vertexShader: require('../glsl/sprite.vert')

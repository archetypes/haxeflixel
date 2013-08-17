guard :shell do
  watch(%r{^test/.+Test\.hx|src/.+\.hx}) do |m|
    `haxelib run munit test -neko`
  end
end
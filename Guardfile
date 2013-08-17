guard :shell do
  watch(%r{^test/.+Test\.hx|source/.+\.hx}) do |m|
    `haxelib run munit test -neko`
  end
end
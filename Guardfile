guard :shell do
  watch(%r{^test/.+Test\.hx|src/.+\.hx}) do |m|
    `rake test`
  end
end
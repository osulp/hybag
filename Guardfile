guard 'rspec', :cli => '--color --drb --format documentation' do
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$})     { |m| ["spec/lib/#{m[1]}_spec.rb", "spec/lib/hybag/baggable_spec.rb"] }
  watch('spec/spec_helper.rb')  { "spec" }
end
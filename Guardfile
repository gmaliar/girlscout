# frozen_string_literal: true

guard :minitest, all_on_start: false do
  watch(%r{^test/(.*)\/?(.*)_test\.rb$})
  watch(%r{^lib/(.*/)?([^/]+)\.rb$}) { |m| "test/#{m[1]}#{m[2]}_test.rb" }
  watch(%r{^test/support\.rb$}) { 'test' }
end

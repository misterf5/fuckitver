.PHONY: default
default: build

node_modules: package.json yarn.lock
	yarn && touch $@

npmScripts := build start fmt fmt-check
.PHONY: ${npmScripts}
${npmScripts}: node_modules
	yarn $@

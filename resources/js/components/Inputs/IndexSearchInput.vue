<template>
  <div class="relative w-full md:w-1/3 md:shrink-0 ">
    <Icon
      name="magnifying-glass"
      type="mini"
      class="absolute ml-2 text-gray-400 top-[4px]"
    />

    <RoundInput
      dusk="search-input"
      class="bg-gray-100 dark:bg-gray-800 dark:focus:bg-gray-800"
      :placeholder="__('Search')"
      type="search"
      v-model="keyword"
      spellcheck="false"
      :aria-label="__('Search')"
      data-role="resource-search-input"
    />
  </div>
</template>

<script setup>
import {Icon} from 'laravel-nova-ui'
import {useLocalization} from '@/composables/useLocalization'

const { __ } = useLocalization()

const keyword = defineModel()
</script>

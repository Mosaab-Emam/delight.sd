<template>
  <div>
    <div class="text-9xl text-teal mb8">
      Delight.SD
    </div>
    <div class="text-xl">
      عائلة تطبيقات سودانية. مقدمة لكم بواسطة <a href="https://mosaabemam.com" class="text-teal">مصعب الإمام</a>
    </div>
    <Logos mb-6 />
    <Suspense>
      <PageView />
      <template #fallback>
        <div op50 italic>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
    <InputEntry />
  </div>
</template>

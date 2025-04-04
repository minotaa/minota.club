<script lang="ts">
  //let info = infoDump[Math.floor((Math.random()*infoDump.length))]

  function copyToClipboard(e: Event) {
    e.preventDefault()
    navigator.clipboard.writeText('minota')
      .catch(err => {
        console.error(err)
      })
  }
</script>

<div class="md:container md:mx-auto flex mx-auto flex-col pt-8 gap-4 mb-4">
  <div class="flex md:flex-row flex-col">
    <h1 class="text-2xl text-slate-200 font-bold text-center md:text-left"><strong class="text-sky-300">minota</strong></h1>
    <h2 class="text-lg text-slate-500 md:ml-3 mt-1 text-center md:text-left">he/him</h2>
  </div>
  <h2 class="text-lg text-slate-300 -mt-2 mb-2 text-center md:text-left">
    <a class="transition-colors hover:text-sky-400" target="_blank" href="https://discord.gg/8WAPWCFu8m">Discord</a> /
    <a class="transition-colors hover:text-sky-400" target="_blank" href="https://github.com/minotaa">GitHub</a> /
    <a class="transition-colors hover:text-sky-400" target="_blank" href="https://bsky.app/profile/minota.cc">Bluesky</a> /
    <a class="transition-colors hover:text-sky-400" target="_blank" href="https://ko-fi.com/minota">Ko-fi</a> /
    <a class="transition-colors hover:text-sky-400" href="mailto:me@minota.cc">Email</a>
  </h2>
  <h1 class="text-xl text-slate-200 font-bold text-center md:text-left">projects</h1>
  <div class="flex flex-col flex-wrap md:flex-row gap-2 md:place-self-start place-self-center">
    <div class="shadow-lg rounded-lg p-4 w-80 pr-8 h-200 bg-zinc-900 border-2 border-zinc-700">
      <h2 class="text-slate-300 text-lg font-bold">Xestra UHC; Notzo UHC; applejuice (2018 - 2024)</h2>
      <h3 class="mt-2 text-zinc-400 text-md italic mb-4">
        applejuice was an <a class="transition-colors text-sky-300 hover:text-sky-400" target="_blank" href="https://minecraft.fandom.com/wiki/Tutorials/Ultra_hardcore_survival">Ultra Hardcore</a> (or UHC) Minecraft server I made in 2022. 
        It's notable for being the first UHC server I made in Kotlin. The source code for the plugin used can be found below.
      </h3>
      <a title="Open applejuice source code" href="https://github.com/applejuice-server/Kraftwerk" target="_blank" class="shadow-lg rounded-xl pt-2 pb-2 pl-4 pr-4 bg-sky-400 hover:bg-sky-500 transition-colors">Source Code</a>
    </div>
  
    <div class="shadow-lg rounded-lg p-4 w-80 pr-8 h-200 bg-zinc-900 border-2 border-zinc-700">
      <h2 class="text-slate-300 text-lg font-bold">piglin.club (2023)</h2>
      <h3 class="mt-2 text-zinc-400 text-md italic mb-4">
        piglin.club was the second server I made during 2022/2023. It's primarily a 1.20 Towny server that has elements of RPGs like skills, custom crafts, etc.
        It largely was ended due to running into problems thinking of ways to make the game more creative.
      </h3>
      <a title="Open piglin.club source code" href="https://github.com/PiglinClub/Brimstone" target="_blank" class="shadow-lg rounded-xl pt-2 pb-2 pl-4 pr-4 bg-sky-400 hover:bg-sky-500 transition-colors">Source Code</a>
    </div>

    <div class="shadow-lg rounded-lg p-4 pr-8 w-80 h-200 bg-zinc-900 border-2 border-zinc-700">
      <h2 class="text-slate-300 text-lg font-bold">wushi (2019? - 2021)</h2>
      <h3 class="mt-2 text-zinc-400 text-md italic mb-4">
        wushi was a Discord bot made in Node.js and then later on made in TypeScript. There isn't really much to say about it! I thought it was cool!
      </h3>
      <a title="Open wushi bot source code" href="https://github.com/wushi-bot/wushi" target="_blank" class="shadow-lg rounded-xl mt-3 pt-2 pb-2 pl-4 pr-4 bg-sky-400 hover:bg-sky-500 transition-colors place-end">Source Code</a>
    </div>

    <div class="shadow-lg rounded-lg p-4 pr-8 w-80 h-200 bg-zinc-900 border-2 border-zinc-700">
      <h2 class="text-slate-300 text-lg font-bold">Beachside Tactics (2024)</h2>
      <h3 class="mt-2 text-zinc-400 text-md italic mb-4">
        Internally known as Rhode Island. It is my first available Godot game. It's a small fishing game where you fish for fish to get more rods, baits, etc. It's still available on the App Store right now!
      </h3>
      <div class="flex flex-col w-fit place-end">
        <a title="Get Beachside Tactics" href="https://apps.apple.com/us/app/beachside-tactics/id6596775495?itscg=30200&itsct=apps_box_badge&mttnsubad=6596775495" target="_blank" class="shadow-lg rounded-xl pt-2 pb-2 mt-3 pl-4 pr-4 bg-sky-400 hover:bg-sky-500 transition-colors">App Store</a>
      </div>
    </div>

    <div class="shadow-lg rounded-lg p-4 pr-8 w-80 h-200 bg-zinc-900 border-2 border-zinc-700">
      <h2 class="text-slate-300 text-lg font-bold">Myrkwood (or Mirkwood) (2024-2025)</h2>
      <h3 class="mt-2 text-zinc-400 text-md italic mb-4">
        Murkwood? Myrkwood is a game inspired by an old Flash game, Three Goblets, in which you progress through the game by automatically fighting enemies and crafting items from its drops. Now on the App Store.
      </h3>
      <div class="flex flex-col w-fit place-end">
        <a title="Get Myrkwood" href="https://apps.apple.com/us/app/myrkwood/id6738539616" target="_blank" class="shadow-lg rounded-xl pt-2 pb-2 mt-3 pl-4 pr-4 bg-sky-400 hover:bg-sky-500 transition-colors">App Store</a>
      </div>
    </div>


    <div class="shadow-lg rounded-lg p-4 pr-8 w-80 h-200 bg-zinc-900 border-2 border-zinc-700">
      <h2 class="text-slate-300 text-lg font-bold">Bulletlane (2025)</h2>
      <h3 class="mt-2 text-zinc-400 text-md italic mb-4">
        Bulletlane is the third and newest game I made, it's a car based shoot 'em up in which you defeat enemies, get powerups, and upgrade your weapons, cars, and other stuff. It was inspired by an old game I played on the App Store, now I made a new version of it. Now on the App Store.
      </h3>
      <div class="flex flex-col w-fit place-end">
        <a title="Get Bulletlane" href="https://apps.apple.com/us/app/bulletlane/id6743356289" target="_blank" class="shadow-lg rounded-xl pt-2 pb-2 mt-3 pl-4 pr-4 bg-sky-400 hover:bg-sky-500 transition-colors">App Store</a>
      </div>
    </div>

    <div class="shadow-lg rounded-lg p-4 pr-8 w-80 h-200 bg-zinc-900 border-2 border-zinc-700">
      <h2 class="text-slate-300 text-lg font-bold">ultrahardcore.org (2022 - 2024)</h2>
      <h3 class="mt-2 text-zinc-400 text-md italic mb-4">
        My first Svelte project. It was intended to be a replacement website for <a class="transition-colors text-sky-300 hover:text-sky-400" target="_blank" href="https://uhc.gg">uhc.gg</a>, which is another calendar website for posting UHC matches.
      </h3>
      <div class="flex flex-col w-fit place-end">
        <a title="Open ultrahardcore.org source code" href="https://github.com/minotaa/ultrahardcore.org" target="_blank" class="shadow-lg rounded-xl pt-2 pb-2 pl-4 pr-4 bg-sky-400 hover:bg-sky-500 transition-colors">Source Code</a>
      </div>
    </div>
  </div>
</div>

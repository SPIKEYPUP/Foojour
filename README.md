<H1> General Introduction... <i>What Is FooJour??</i></H1>

  <p>In General <b><i>"Foojour"</i></b> is my way of trying to push the creative envelope within myself to create either new and useful, or interesting and appealing components, scripts, and general code for the Foobar2K Ecosystem.  If you have not tried Foobar2K for all of your music playing needs, well then my friend, look no further.</p>

<H2>Relevant Links and References</H2>
  
  
  <B> Foobar2K Downloads <i>(Android, iOS, Windows)</i></B><lf>

<p><a href="https://www.foobar2000.org/" title="foobar2000 homepage"><img
  src="https://www.foobar2000.org/button-large.png" alt="foobar2000 audio player" width="110" height="32" /></a></p><break>
  
  
  <p><B>https://www.foobar2000.org/</B></p>
  <p><B>https://www.foobar2000.org/download</B></p>
  
  <p><B>SDK And Visual Studio Projects/Solutions Available:</B><p>
  <p></p>
  <p><b>https://www.foobar2000.org/SDK</b></p>

<b><i>
<sub>Foobar2K features a very active developer group that works on components, core, DSP, functionality, display, etc. for the multi-talented player and media library manager.
</i></b></sub>

<p><heading>My Foobar Facts:</heading></p>
<p></p>
<p>1. I currently have about <B>6,000+ Albums in my Database</B><i><b>  That equates to about 110,000 Music Files!</b></i></p>

<p>2. I have files that go as low as 64Kbps MP3 VBR0, to full 6 Channel DTS Decoded (FLAC) 24Bit-96Khz files ,<i>(if you are wondering in FLAC it is roughly 6Mbps-8Mbps or 6,000Kbps-8,000Kbps for those files, and yes, <u><b>they sound amazing.</b></u></i></p>

<p>3. Although I enjoy listening sessions using WASAPI Event Mode or ASIO/Kernel Mode (No Latency or upwards of 30ms HW Buffer) for bit-perfect or bit-matched playback.  I typically just use the hardware mixer output available through Direct Sound because I stream games and what not and I need to hear everything else too!  <i><b>Note:</b> If you use WASAPI/ASIO/Kernel 9 out of 10 times this will mute your other sounds, as it should, so all you and your computer are focused on is your tunes!</i></p>

<p>4. I absolutely do use a DSP chain!  It's not long, but it's there!  I use Dynamic Compressor to fill out the sound and get it jammin' the way I like it, then I apply SOX Resampler to push the samples to 96Khz on all files (if you do this you need to modify your tone sweep rates in Advanced Foobar Config, or your visuals and some processing will be totally hillarious).</p>

<p>5. My output target is set at 24Bit 96Khz 6 Channels / 5.1 Channles....soon going to 7.1!  <i>Muahahahahahah!</i></p>

<p>6. Yes I feel there is a difference using 24Bit and especially 96KhzSR, it's subtle and mostly a distinction feeling, like an airiness, but most will probably not notice...sigh.</p>

<p>7. <b><i>Fun Fact!</i></b>  The Codecs, DACs and DSPs on my sound card are capable of producing and processing 32-Bit 192Khz Stereo Resolution in realtime!  I tired it... works great, but not worth the insane overhead if not going Kernel or WASAPI, and even then...overhead.  Think about it, it's a lot of data that you are asking to be played back in zero_latency mode.  Plus I don't have any Wilson Watt Puppy's to throw at it, if ya know what I mean...</p>

<p>8. I'll post some pictures so you can see my favorite layouts of Foobar2K using standard UI.  I don't use columns, not a preference, just never tried it.  I will soon though, there is a whole new world of coding available with Columns UI for Foobar2K.</p>

<p>9. I use Foobar2K for pretty much ALL of my library needs: tagging, Converting, large search queries, Importing, Ripping, Upsampling, Basic Audio Analysis, Meta Tag Management, etc...</p>

<p>10. I operate my own FreeDB MusicBrainz server to catalogue and keep my collection up to date with tags, comments, ratings, reviews and artwork.  It's 50GB, but it's worth it!  When I want to catalogue I just spin up the VM (it runs on Ubuntu Linux), get a current replication update, wait a day for that to finish, create indexes, wait another day for that to finish, then boom!  Away I go!  It is by far faster having the server local handling my requests only, it's at least 10,000% faster, and if you've tried to index and catalog your collection from a public freeDB server, you know exactly what I mean.  They're slammed!  So if you have a large collection, I recommend D/L the VM, replicating to get current (then setup auto replication and turn the VM on for a couple days a week to sync and index) and then let Foobar2K use it as a local tagging source, setup your desired tag pulls, and go to town!  It costs ZILCH to do, and it's pretty dang easy, the folks running MusicBrainz have already done all the hard work, just plop it into VirtualBox (Oracle VM Player) and get replicating!  Plus... if you have a more obscure but well tagged collection, you can add to the repository as well by replicating two-way with the public servers.  Share the wealth I always say!</p>

<p>11. Thanks for your interest in Foobar2K and in my little code tidbits!  You can always catch me broadcasting on Youtube as SPIKEYPUP, or on Twitch.tv/spikeypup1, hitbox, dailymotion, etc.  Just search for the pup using SPIKEYPUP.  See you there!</p>

<p>This project was created and authored by Patrick Ewalt A.K.A. SPIKEYPUP under the MIT Software license.  Enjoy and mutate it folks! If you do recycle and share this code please do make a mention for me if you could or send them back to this Github Repo!  Thanks!</p>


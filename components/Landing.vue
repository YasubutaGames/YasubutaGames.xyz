<style>
.title {
  font-size: 3.5em;
  margin: 0;
  font-weight: bold;
}
.title .smolText {
  font-size: 15px;
}
.image {
  width: 100%;
  border-radius: 5px;
}
@font-face {
  font-family: "pixelFont";
  src: url("/PIXELADE.TTF");
}
.background {
  font-family: pixelFont;
  color: #ffffdc;
}
body {
  background-color: #4a3b99;
}
.content.strong {
  font-size: 35px;
}
.content.patch {
  font-size: 25px;
}
.whitespaceSmall {
  margin-top: 25px;
}
.whitespaceBig {
  margin-top: 50px;
}
.liImage {
  width: 100%;
  list-style: none;
}
.liContent {
  list-style: square;
}
ul {
  list-style-position: outside;
  margin: 4px 0 0 16px;
  padding: 0;
}
.date {
  float: right;
  margin: 0;
  padding: 0;
}
.statusComplete {
  float: right;
  color: #41be71;
}
.statusError {
  float: right;
  color: #be4156;
}
.issueArrow {
  margin: -4.5px;
  margin-left: 1px;
}
.issueDetails {
  background-color: #be4156;
  border-radius: 5px;
  padding: 2px 5px 2px 8px;
  margin-top: 5px;
}
.issueFloatRight {
  float: right;
}
.severityGreen {
  color: #46e282;
  font-size: 20px;
}
.severityYellow {
  color: #fae154;
  font-size: 20px;
}
.severityRed {
  color: #ff9090;
  font-size: 20px;
}
.paragraphLessMargin {
  margin: 5px;
  text-decoration-line: underline;
}
.statusInProgress {
  float: right;
  color: #339659;
}
.statusNotYet {
  float: right;
  color: #705ae8;
}
.floatRight {
  float: right;
}
.smolArrow {
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: 23px;
  width: 75%;
}
.smolArrowNoMargin {
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: 0px;
  width: 75%;
}
.noMarginBottom {
  margin-bottom: 0;
}
.centeredText {
  text-align: center;
}
a {
  color: #ffffdc;
  text-decoration: none;
}
a:hover {
  color: #c4ceff;
}
.bubble {
  background-color: #0b4c33;
  border-radius: 5px;
  padding: 2px 5px 0px 8px;
  margin-top: 5px;
}
.bubbleLong {
  background-color: #0b4c33;
  border-radius: 5px;
  padding: 2px 5px 0px 8px;
  margin-top: 5px;
  margin-bottom: 3px;
}
.moreData {
  cursor: pointer;
}
.moreData:hover {
  color: #c4ceff;
}
.svg {
  width: 25px;
  position: absolute;
  right: 0;
  top: 0;
}
.titleTwitter {
  right: 0;
  top: -15px;
}
.titleGooglePlay {
  right: 0;
  top: 3px;
}
.isRelative {
  position: relative;
}
.isAbsolute {
  position: absolute;
  right: 4px;
  top: 2px;
}
.smolArrowPosition {
  right: 50px;
  top: 0px;
}
.hasHeight {
  height: 60px;
}
@media screen and (min-width: 500px) {
  .background {
    width: 500px;
    margin: auto;
  }
  .smolArrow {
    display: block;
    margin-left: 75px;
    margin-right: 0px;
    margin-top: 23px;
    width: 382px;
  }
  .smolArrowNoMargin {
    display: block;
    margin-left: 75px;
    margin-right: 0px;
    margin-top: 0px;
    width: 382px;
  }
}
</style>

<template>
  <div class="background">
    <div class="title isRelative">
      Yasubuta Games<span class="smolText"> . x y z</span>
      <div class="svg titleTwitter">
        <a href="https://twitter.com/YasubutaGames"
          ><svg
            stroke="currentColor"
            fill="currentColor"
            stroke-width="0"
            viewBox="0 0 512 512"
            height="25px"
            width="25px"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
            ></path></svg
        ></a>
      </div>
    </div>

    <p>
      Welcome to our home! Below you'll find information about us and our
      projects. Follow us on twitter for the latest updates & information.
    </p>

    <div class="whitespaceBig"></div>

    <div class="content strong centeredText isRelative">
      The Viridian Obelisk
      <div class="svg titleGooglePlay">
        <a
          href="https://play.google.com/store/apps/details?id=com.YasubutaGames.TheViridianObelisk"
          ><svg
            stroke="currentColor"
            fill="currentColor"
            stroke-width="0"
            viewBox="0 0 512 512"
            height="25px"
            width="25px"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M325.3 234.3L104.6 13l280.8 161.2-60.1 60.1zM47 0C34 6.8 25.3 19.2 25.3 35.3v441.3c0 16.1 8.7 28.5 21.7 35.3l256.6-256L47 0zm425.2 225.6l-58.9-34.1-65.7 64.5 65.7 64.5 60.1-34.1c18-14.3 18-46.5-1.2-60.8zM104.6 499l280.8-161.2-60.1-60.1L104.6 499z"
            ></path></svg
        ></a>
      </div>
    </div>

    <p class="centeredText">
      <i>Quick Introduction</i>
    </p>
    <p>
      The Viridian Obelisk is a Semi-Idle, Side-Scroller, RPG. As such, your
      character may battle on their own. However, with your oversight and input,
      your capabilities will significantly increase.
    </p>
    <p>
      You'll start out weak & fragile, but by grinding & sheer will you'll
      slowly but surely grow stronger and stronger. You'll battle through
      dungeons, bosses and timed challenge levels. You'll find rare items, learn
      powerful spells, and empower your character.
    </p>
    <p>
      Should you persevere, you'll reach the object of your obsession, the end
      of your quest; the Viridian Obelisk.
    </p>
    <p class="centeredText">
      <i>Lore & Story</i>
    </p>
    <p>
      As the world is thrown into chaos and hope fades, adventurers gather to
      uncover the secrets of the Ancient Gods.
    </p>
    <p>
      A perpetual war has been raging across the known lands. Three factions
      have struggled for supremacy.
    </p>
    <p>
      The Guild of the Grand Magus; an archaic cult of mages, constantly in
      search for novel ways to manipulate, harvest & utilize arcane energy. With
      their intellect, wisdom & cunning, they seek to outsmart & outlast their
      foes.
    </p>
    <p>
      The Order of the Holy Blade; righteous zealots, whose ambitions are
      overshadowed by none other. Through divine insight & ability, they face
      any threat without fear. But, their brutal methods & fundamentalism
      garners strong foes.
    </p>
    <p>
      The Clan of the Hollow Skull; once savage tribal communities, now united
      under one creed. Its members value strength & might above all else. A
      culture that spawns fierce, uncompromising warriors.
    </p>
    <p>
      At the height of turmoil, a faint rumor is heard; one of the Lost Obelisks
      has resurfaced.
    </p>
    <p>The Viridian Obelisk.</p>
    <p class="centeredText">
      <i>Goals, Design Approach, In-depth Gameplay & More</i>
    </p>
    <p>
      With the Viridian Obelisk, our main goal was to create a role-playing game
      with the focus on a relaxing and satisfying player experience. The game
      plays in portrait mode, minimum oversight is required, progression is slow
      but steady.
    </p>
    <p>
      The game contains no ads, microtransactions or other immersion breaking
      elements.
    </p>
    <p>Another important focus for us is player choice.</p>
    <p>
      Firstly; playstyles. The game can be played in short bursts, or for a
      prolonged amount of time, depending on what your prefer. Due to in-game
      mechanics, your character will be stronger if you're paying attention and
      doing everything you can to help your character advance.
    </p>
    <p>
      However, you may also, for the most part, let the game play by itself.
      When an obstacle that requires your input is presented, your device will
      notify you, allowing your to respond accordingly.
    </p>
    <p>
      Whichever style will allow your character to progress, albeit at different
      paces.
    </p>
    <p>
      Secondly; character customization. Building you character is an important
      part of the Viridian Obelisk. At creation you'll choose your faction
      allegiance and heritage. These will impact how you're perceived and
      treated in the game world.
    </p>
    <p>
      Progressing through the game you'll choose your weapons, armor,
      accessories, spells & attributes. Upgrade and combine these to create
      powerful & versatile builds that fit your style of play.
    </p>
    <p>
      Thirdly; story & world interaction. The story is present, but not
      obligatory. If you take the time to read conversations, in-game
      discoveries etc., there's a narrative observable throughout the game.
      We've built a cohesive fantasy world, with factions, characters, locations
      and lore.
    </p>
    <p>
      But, we understand that's not something everyone wishes to partake in.
      Some may just want to slay monsters, level up, slay stronger monsters,
      repeat. Which is of course valid. For that reason the story, in general,
      will not interrupt gameplay.
    </p>
    <p>
      We hope you'll have as much fun playing the Viridian Obelisk as we have
      developing it. If you have any suggestions, feedback or questions, contact
      us at:
      <a href="mailto: yasubutagames@gmail.com">YasubutaGames@gmail.com</a>
    </p>

    <div class="whitespaceSmall"></div>
    <div id="Status" class="content strong centeredText">Game Status</div>
    <p>
      Standard Version, {{ this.logs[0].version }}.

      <span
        v-if="
          this.issues[0].isActive == true &&
          this.issues[0].version == this.logs[0].version
        "
      >
        <i class="statusError bubble"
          >. . . ISSUES FOUND
          <span
            v-if="moreIssueInfo != true"
            class="issueArrow statusError moreData"
            @click="showMoreIssueInfo()"
          >
            ➡
          </span></i
        >
      </span>
      <span v-else>
        <i class="statusComplete bubble">. . . NO ISSUES FOUND</i>
      </span>
    </p>

    <div v-if="moreIssueInfo == true">
      <div v-for="issue of issues" :key="issue">
        <div class="issueDetails" v-if="issue.isActive == true">
          <p class="paragraphLessMargin">
            Report Date: <span class="issueFloatRight">{{ issue.date }}</span>
          </p>
          <p class="paragraphLessMargin">
            Type: <span class="issueFloatRight">{{ issue.type }}</span>
          </p>
          <p class="paragraphLessMargin">
            Severity:
            <span v-if="issue.severity == 0" class="issueFloatRight"
              ><span class="severityGreen">Low</span>/Mid/High</span
            >
            <span v-else-if="issue.severity == 1" class="issueFloatRight"
              >Low/<span class="severityYellow">Mid</span>/High</span
            >
            <span v-else-if="issue.severity == 2" class="issueFloatRight"
              >Low/Mid/<span class="severityRed">High</span></span
            >
            <span v-else class="issueFloatRight">Unknown Severity</span>
          </p>
          <p class="paragraphLessMargin">
            Description:
            <span class="issueFloatRight">{{ issue.description }}</span>
          </p>
        </div>
      </div>
    </div>

    <div class="whitespaceSmall"></div>
    <p>
      Trial Version, 0.126i.
      <i class="statusComplete bubble">. . . NO ISSUES FOUND</i>
    </p>
    <p>
      <a class="floatRight" href="mailto: yasubutagames@gmail.com"
        >Report Issue</a
      >
    </p>

    <div class="whitespaceSmall"></div>
    <div class="whitespaceBig"></div>
    <div id="ChangeLog" class="content strong centeredText">Change Log</div>
    <div class="whitespaceSmall"></div>

    <div>
      <p v-if="$fetchState.pending">Fetching Logs...</p>
      <p v-else-if="$fetchState.error">An error occurred :(</p>
      <div v-else-if="moreLogs == false">
        <div class="bubbleLong isRelative">
          {{ this.logs[0].title }} : {{ this.logs[0].version }}
          <p class="date isAbsolute">
            {{ this.logs[0].date }}
          </p>
        </div>

        <div v-if="this.logs[0].image != ''">
          <li class="liImage" v-for="i of this.logs[0].image" :key="i">
            <img class="image" :src="i" />
          </li>
        </div>
        <ul>
          <li class="liContent" v-for="c of this.logs[0].content" :key="c">
            {{ c }}
          </li>
        </ul>
        <div class="whitespaceSmall"></div>

        <p class="centeredText moreData" @click="showMoreLogs()">More</p>
      </div>
      <div v-else>
        <div v-for="log of logs" :key="log">
          <div class="bubbleLong isRelative">
            {{ log.title }} : {{ log.version }}
            <p class="date isAbsolute">
              {{ log.date }}
            </p>
          </div>
          <div v-if="log.image != ''">
            <li class="liImage" v-for="i of log.image" :key="i">
              <img class="image" :src="i" />
            </li>
          </div>
          <ul>
            <li class="liContent" v-for="c of log.content" :key="c">
              {{ c }}
            </li>
          </ul>
          <div class="whitespaceBig"></div>
        </div>
      </div>
    </div>

    <div class="whitespaceBig"></div>
    <div id="Roadmap" class="content strong centeredText">Roadmap</div>
    <p class="centeredText"><i>-- Main Missions</i></p>
    <div class="whitespaceSmall"></div>
    <p class="noMarginBottom">
      2022, Q1: Base Game Release; Complete testing & publish The Viridian
      Obelisk on Google Play!
    </p>
    <div class="isRelative hasHeight">
      <i class="statusComplete bubble">. . . COMPLETE</i>
      <img
        class="smolArrow isAbsolute smolArrowPosition"
        src="/smolArrowComplete.png"
      />
    </div>

    <p>
      2022, Q2: Post-Release Improvements; Polish, bug-squashing, feedback
      integration.
    </p>
    <p
      v-if="moreRoadmapInfoQ2 != true"
      class="centeredText moreData"
      @click="showMoreRoadmapInfoQ2()"
    >
      More
    </p>
    <p v-else>
      We still have a couple of things that we wish to accomplish in this phase.
      We're currently working on adding unique music to boss fights, and
      potentially to certain in-game events. We also want to create custom
      animations for most, if not all, spells. Furthermore, player attack
      animations is something we wish to add and improve upon in the future.
      This may however be delayed to a later phase, in favor of new content.
    </p>
    <div class="isRelative hasHeight">
      <i class="statusInProgress bubble">. . . IN PROGRESS: 96%</i>
      <img
        class="smolArrow isAbsolute smolArrowPosition"
        src="/smolArrowInProgress.png"
      />
    </div>

    <p>
      2022, Q3: Content Expansion; "The Demonic Realm". Journey to the
      stronghold of the demons to put an end to their diabolical mischief, once
      and for all. New Dungeons, Bosses, Items, Spells & Increased Level/Upgrade
      cap.
    </p>
    <p
      v-if="moreRoadmapInfoQ3 != true"
      class="centeredText moreData"
      @click="showMoreRoadmapInfoQ3()"
    >
      More
    </p>
    <p v-else>
      This will be our first mayor content expansion. We're still currently in
      the planning phase, but we've made some general decisions regarding what
      we wish to accomplish. Right now we're looking to add 3 additional
      progression dungeons, 3 challange dungeons, and 10 new bosses (3 for each
      progression dungeon, and lastly a final boss). Defeating bosses will most
      likely be the main method of power progression. For example, defeating the
      first new boss might raise your level cap to 105. Defeating the second
      boss might allow you to further upgrade your weapon & equipment, etc.
    </p>
    <div class="isRelative hasHeight">
      <i class="statusInProgress bubble">. . . IN PROGRESS: 12%</i>
      <img
        class="smolArrow isAbsolute smolArrowPosition"
        src="/smolArrowInProgress.png"
      />
    </div>

    <p>
      2022, Q4: Content Expansion; "The Lost Frontier". Regroup with your
      faction, battle for glory & treasure in a newly discovered mysterical
      realm. New Dungeons, Bosses, Items, Spells & Increased Level/Upgrade cap.
      <i class="statusNotYet bubble">. . . NOT YET STARTED</i>
    </p>
    <div class="whitespaceSmall"></div>
    <p class="centeredText"><i>-- Side Missions</i></p>
    <p>
      2022: Translation; Japanese.
      <i class="statusNotYet bubble">. . . PAUSED</i>
    </p>
    <i>Note: Roadmap not final. Last update: {{ this.logs[0].date }}</i>

    <div class="whitespaceBig"></div>
    <div id="PrivacyPolicy" class="content strong centeredText">
      Privacy Policy
    </div>
    <p>
      Anton Fogelstroem built the The Viridian Obelisk app as a Commercial app.
      This SERVICE is provided by Anton Fogelstroem and is intended for use as
      is.
    </p>
    <p>
      This page is used to inform visitors regarding my policies with the
      collection, use, and disclosure of Personal Information if anyone decided
      to use my Service.
    </p>
    <p>
      If you choose to use my Service, then you agree to the collection and use
      of information in relation to this policy. The Personal Information that I
      collect is used for providing and improving the Service. I will not use or
      share your information with anyone except as described in this Privacy
      Policy.
    </p>
    <p>
      The terms used in this Privacy Policy have the same meanings as in our
      Terms and Conditions, which are accessible at The Viridian Obelisk unless
      otherwise defined in this Privacy Policy.
    </p>
    <p><i>Information Collection and Use</i></p>
    <p>
      For a better experience, while using our Service, I may require you to
      provide us with certain personally identifiable information. The
      information that I request will be retained on your device and is not
      collected by me in any way.
    </p>
    <div>
      <p>
        The app does use third-party services that may collect information used
        to identify you.
      </p>
      <p>
        Link to the privacy policy of third-party service providers used by the
        app
      </p>
      <ul>
        <li>
          <a
            href="https://www.google.com/policies/privacy/"
            target="_blank"
            rel="noopener noreferrer"
            >Google Play Services</a
          >
        </li>
        <!----><!----><!----><!----><!----><!----><!----><!----><!----><!---->
        <li>
          <a
            href="https://unity3d.com/legal/privacy-policy"
            target="_blank"
            rel="noopener noreferrer"
            >Unity</a
          >
        </li>
        <!----><!----><!----><!----><!----><!----><!----><!----><!----><!----><!----><!----><!----><!----><!----><!---->
      </ul>
    </div>
    <p><i>Log Data</i></p>
    <p>
      I want to inform you that whenever you use my Service, in a case of an
      error in the app I collect data and information (through third-party
      products) on your phone called Log Data. This Log Data may include
      information such as your device Internet Protocol (“IP”) address, device
      name, operating system version, the configuration of the app when
      utilizing my Service, the time and date of your use of the Service, and
      other statistics.
    </p>
    <p><i>Cookies</i></p>
    <p>
      Cookies are files with a small amount of data that are commonly used as
      anonymous unique identifiers. These are sent to your browser from the
      websites that you visit and are stored on your device's internal memory.
    </p>
    <p>
      This Service does not use these “cookies” explicitly. However, the app may
      use third-party code and libraries that use “cookies” to collect
      information and improve their services. You have the option to either
      accept or refuse these cookies and know when a cookie is being sent to
      your device. If you choose to refuse our cookies, you may not be able to
      use some portions of this Service.
    </p>
    <p><i>Service Providers</i></p>
    <p>
      I may employ third-party companies and individuals due to the following
      reasons:
    </p>
    <ul>
      <li>To facilitate our Service;</li>
      <li>To provide the Service on our behalf;</li>
      <li>To perform Service-related services; or</li>
      <li>To assist us in analyzing how our Service is used.</li>
    </ul>
    <p>
      I want to inform users of this Service that these third parties have
      access to their Personal Information. The reason is to perform the tasks
      assigned to them on our behalf. However, they are obligated not to
      disclose or use the information for any other purpose.
    </p>
    <p><i>Security</i></p>
    <p>
      I value your trust in providing us your Personal Information, thus we are
      striving to use commercially acceptable means of protecting it. But
      remember that no method of transmission over the internet, or method of
      electronic storage is 100% secure and reliable, and I cannot guarantee its
      absolute security.
    </p>
    <p><i>Links to Other Sites</i></p>
    <p>
      This Service may contain links to other sites. If you click on a
      third-party link, you will be directed to that site. Note that these
      external sites are not operated by me. Therefore, I strongly advise you to
      review the Privacy Policy of these websites. I have no control over and
      assume no responsibility for the content, privacy policies, or practices
      of any third-party sites or services.
    </p>
    <p><i>Children’s Privacy</i></p>
    <div>
      <p>
        These Services do not address anyone under the age of 13. I do not
        knowingly collect personally identifiable information from children
        under 13 years of age. In the case I discover that a child under 13 has
        provided me with personal information, I immediately delete this from
        our servers. If you are a parent or guardian and you are aware that your
        child has provided us with personal information, please contact me so
        that I will be able to do the necessary actions.
      </p>
    </div>
    <!---->
    <p><i>Changes to This Privacy Policy</i></p>
    <p>
      I may update our Privacy Policy from time to time. Thus, you are advised
      to review this page periodically for any changes. I will notify you of any
      changes by posting the new Privacy Policy on this page.
    </p>
    <p>This policy is effective as of 2022-04-22</p>
    <p><i>Contact Us</i></p>
    <p>
      If you have any questions or suggestions about my Privacy Policy, do not
      hesitate to contact me at YasubutaGames@gmail.com.
    </p>
    <p>
      This privacy policy page was created at
      <a
        href="https://privacypolicytemplate.net"
        target="_blank"
        rel="noopener noreferrer"
        >privacypolicytemplate.net </a
      >and modified/generated by
      <a
        href="https://app-privacy-policy-generator.nisrulz.com/"
        target="_blank"
        rel="noopener noreferrer"
        >App Privacy Policy Generator</a
      >
    </p>
    <div class="whitespaceBig"></div>
    <a
      href="https://play.google.com/store/apps/details?id=com.YasubutaGames.TheViridianObelisk"
      ><svg
        stroke="currentColor"
        fill="currentColor"
        stroke-width="0"
        viewBox="0 0 512 512"
        height="15px"
        width="15px"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M325.3 234.3L104.6 13l280.8 161.2-60.1 60.1zM47 0C34 6.8 25.3 19.2 25.3 35.3v441.3c0 16.1 8.7 28.5 21.7 35.3l256.6-256L47 0zm425.2 225.6l-58.9-34.1-65.7 64.5 65.7 64.5 60.1-34.1c18-14.3 18-46.5-1.2-60.8zM104.6 499l280.8-161.2-60.1-60.1L104.6 499z"
        ></path></svg
    ></a>
    <a href="https://twitter.com/YasubutaGames"
      ><svg
        stroke="currentColor"
        fill="currentColor"
        stroke-width="0"
        viewBox="0 0 512 512"
        height="15px"
        width="15px"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
        ></path></svg
    ></a>
    <a href="https://github.com/YasubutaGames"
      ><svg
        stroke="currentColor"
        fill="currentColor"
        stroke-width="0"
        viewBox="0 0 24 24"
        height="15px"
        width="15px"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
        /></svg
    ></a>
    <!-- <a href="#"
      ><svg
        stroke="currentColor"
        fill="currentColor"
        stroke-width="0"
        viewBox="0 0 24 24"
        height="15px"
        width="15px"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M19.54 0c1.356 0 2.46 1.104 2.46 2.472v21.528l-2.58-2.28-1.452-1.344-1.536-1.428.636 2.22h-13.608c-1.356 0-2.46-1.104-2.46-2.472v-16.224c0-1.368 1.104-2.472 2.46-2.472h16.08zm-4.632 15.672c2.652-.084 3.672-1.824 3.672-1.824 0-3.864-1.728-6.996-1.728-6.996-1.728-1.296-3.372-1.26-3.372-1.26l-.168.192c2.04.624 2.988 1.524 2.988 1.524-1.248-.684-2.472-1.02-3.612-1.152-.864-.096-1.692-.072-2.424.024l-.204.024c-.42.036-1.44.192-2.724.756-.444.204-.708.348-.708.348s.996-.948 3.156-1.572l-.12-.144s-1.644-.036-3.372 1.26c0 0-1.728 3.132-1.728 6.996 0 0 1.008 1.74 3.66 1.824 0 0 .444-.54.804-.996-1.524-.456-2.1-1.416-2.1-1.416l.336.204.048.036.047.027.014.006.047.027c.3.168.6.3.876.408.492.192 1.08.384 1.764.516.9.168 1.956.228 3.108.012.564-.096 1.14-.264 1.74-.516.42-.156.888-.384 1.38-.708 0 0-.6.984-2.172 1.428.36.456.792.972.792.972zm-5.58-5.604c-.684 0-1.224.6-1.224 1.332 0 .732.552 1.332 1.224 1.332.684 0 1.224-.6 1.224-1.332.012-.732-.54-1.332-1.224-1.332zm4.38 0c-.684 0-1.224.6-1.224 1.332 0 .732.552 1.332 1.224 1.332.684 0 1.224-.6 1.224-1.332 0-.732-.54-1.332-1.224-1.332z"
        /></svg
    ></a> -->
    <div class="footer">
      © 2022 Yasubuta Games. All Rights Reserved. Font Credits: Pixelade by
      Astramat.
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      logs: [],
      issues: [],
      moreLogs: false,
      moreRoadmapInfoQ2: false,
      moreRoadmapInfoQ3: false,
      moreIssueInfo: false,
    };
  },
  refresh() {
    this.fetch.fetchDataChangeLog();
    this.fetch.fetchDataIssues();
  },

  async fetch() {
    await this.fetchDataChangeLog();
    await this.fetchDataIssues();
  },
  methods: {
    async fetchDataChangeLog() {
      this.logs = await fetch(
        "https://raw.githubusercontent.com/YasubutaGames/TheViridianObeliskData/main/ChangeLog.json"
      ).then((res) => res.json());
    },
    async fetchDataIssues() {
      this.issues = await fetch(
        "https://raw.githubusercontent.com/YasubutaGames/TheViridianObeliskData/main/Issues.json"
      ).then((res) => res.json());
    },
    showMoreLogs() {
      this.moreLogs = true;
    },
    showMoreRoadmapInfoQ2(id) {
      this.moreRoadmapInfoQ2 = true;
    },
    showMoreRoadmapInfoQ3(id) {
      this.moreRoadmapInfoQ3 = true;
    },
    showMoreIssueInfo(id) {
      this.moreIssueInfo = true;
    },
  },
};
</script>
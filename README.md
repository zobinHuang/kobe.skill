<div align="center">

![Kobe Bryant — The Mamba Spirit](docs/logo.png)

# Kobe Bryant — The Mamba Spirit

**A Claude Code Skill for Mamba Mentality**

</div>


---


## Overview


`kobe.skill` is a structured knowledge skill that encodes Kobe Bryant's philosophy on **work**, **life**, and **human connection** — collectively known as the **Mamba Spirit**. It is distilled from **87 primary sources** spanning 1996–2025, with **62 successfully extracted** and analyzed, totaling over **221,000 words** of transcripts, articles, speeches, and interviews.


The skill contains:

- **42 verified insights** across work ethic, life philosophy, and social dynamics

- **6 documented contradictions** showing how Kobe's thinking evolved across four career eras

- **7 tentative observations** from single sources awaiting corroboration

- Direct quotes grounded in real transcripts — no fabricated content


### When to Use This Skill


Use this skill when a user asks about:

- Elite performance mindset and deliberate practice

- Competitive psychology and work ethic philosophy

- Leadership under pressure and managing team dynamics

- Career transition and finding purpose after a first career

- Fatherhood, parenting, and leading by example

- Creative pursuits and transferring excellence across domains

- Handling fear, self-doubt, and adversity

- Mentorship — both seeking and providing it

- Mental health in high-performance environments


---


## Installation

### Lightweight Install (Skill Only)

If you just want the skill without the full source corpus:

```bash
# Download only the skill file (~88KB)
curl -sL https://raw.githubusercontent.com/zobinHuang/kobe.skill/main/SKILL.md \
  -o ~/.claude/skills/kobe-mamba-spirit.md
```

### Full Install (Skill + Source Corpus)

```bash
# Clone the full repository with all transcripts and analysis
git clone https://github.com/zobinHuang/kobe.skill.git
```

> **Note:** Audio files (`.mp3`) are excluded via `.gitignore` to keep the repo lightweight (~10MB). Only cleaned transcripts, articles, and metadata are included. If you need to regenerate audio, see the [Contributing](#contributing) section.

### Project Structure

```
kobe.skill/
├── SKILL.md              # The synthesized skill (88KB)
├── analysis.json         # Structured insight analysis (85KB)
├── sources.json          # Master source catalog (87 entries)
├── README.md
├── .gitignore
├── assets/               # Extracted source content (~10MB text)
│   ├── <asset_slug>/
│   │   ├── transcript.md  # Cleaned transcript (video sources)
│   │   ├── content.md     # Article text (text sources)
│   │   ├── meta.json      # Source metadata
│   │   └── subs/          # Raw .vtt subtitle files
│   └── ...
└── docs/
    └── logo.png
```


---


## Collected Sources


The following **58 sources** have been successfully extracted and analyzed, organized chronologically.


### Early Career & Shaq Era (1996–2004)


| # | Date | Title | Source | Summary |
|---|------|-------|--------|---------|
| 1 | 1996-05 | **High School Oral Presentation on NBA vs. College**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/5zr6Xm5IjPM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | ESPN Archive | 17-year-old Kobe delivers a class presentation analyzing why he chose the NBA over college, revealing remarkable poise and analytical thinking. |
| 2 | 1996-07 | **Kobe Bryant 1996 Draft Day Interview & Trade Story**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/eIm_byShLm8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Yahoo Sports / NBA Archive | Kobe's draft day reaction and the story behind being traded from Charlotte to the Lakers. |
| 3 | 1996-10 | **Preseason Halftime Interview with Chick Hearn**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/s5JFEzp4DZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Local Broadcast | Rookie Kobe interviewed at halftime by legendary Lakers broadcaster Chick Hearn during preseason. |
| 4 | 1996-11 | **Kobe Bryant on The Tonight Show with Jay Leno**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/GQ_adibumDQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBC | 18-year-old Kobe's charismatic late-night debut, showcasing the polished media persona that would define his early career. |
| 5 | 1996-12 | **Postgame Kobe Bryant interview from the 1996 Magic Roundball Classic**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/gczagbYOTRg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Local Broadcast | Post-game interview from an early-season classic, showing the raw competitive hunger of a teenage NBA player. |
| 6 | 1998-02 | **1998 NBA All-Star Game Media Availability**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/ijl_ILResKI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBCLA | Young Kobe at the 1998 All-Star Game media session, already projecting supreme confidence among veteran peers. |
| 7 | 1998-03 | **NEXT Issue Cover Story (Inaugural Issue)**<br/>*[Article]* | ESPN The Magazine | Kobe featured on ESPN The Magazine's inaugural 'NEXT' cover alongside A-Rod, Stewart, and Lindros as the future of sports. |
| 8 | 1998-04 | **Show Time! Cover Story**<br/>*[Article]* | Sports Illustrated | SI explores the dichotomy of Kobe's sheltered upbringing and aggressive on-court style. |
| 9 | 2000-04 | **Boy II Man**<br/>*[Article]* | Sports Illustrated | Transitioning from prodigy to championship threat as Kobe matures alongside Shaq. |
| 10 | 2000-06 | **No Fear: NBA Championship Run**<br/>*[Article]* | Sports Illustrated | Kobe's fearless approach during the Lakers' first championship run under Phil Jackson. |
| 11 | 2001-10 | **Kobe Bryant on 60 minutes with Charlie Rose**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/AyXnilND0XM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | 60 Minutes | Kobe discusses injury recovery, the process of rehabilitation, and his refusal to let setbacks define him. |
| 12 | 2003-03 | **Roll of a Lifetime**<br/>*[Article]* | Sports Illustrated | SI coverage during the Lakers' three-peat dynasty era. |

### Solo Star & Championship Peak (2005–2010)


| # | Date | Title | Source | Summary |
|---|------|-------|--------|---------|
| 13 | 2006-01 | **81-Point Game Post-Game Press Conference**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/kEAEKQ8rKCs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBA TV / FSN West | Full press conference after scoring 81 points — the second-highest single-game total in NBA history. Kobe discusses being 'in the moment' and pivots to family duties. |
| 14 | 2006-04 | **The Great Unknown**<br/>*[Article]* | Sports Illustrated | SI explores Kobe's intense compartmentalization and isolated psyche during his solo-star era. |
| 15 | 2008-08 | **The Redeem Team: Olympic Interviews and Segments**<br/>*[video_interview]* | Netflix (Documentary Feature) | How Kobe, LeBron, and USA Basketball's elite subordinated their egos to redeem American basketball at the 2008 Beijing Olympics. |
| 16 | 2009-05 | **Kobe Doin' Work (Spike Lee Documentary)**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/1Fv78gE3u5w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | ESPN Films | Spike Lee's documentary capturing Kobe's real-time tactical communication, Triangle Offense execution, and internal monologue during a single game against the Spurs. |
| 17 | 2009-06 | **Jobs Not Finished: NBA Finals Game 2 Interview**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/fY7l2pcxdHM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBA Broadcast | The iconic 'Job's not finished' moment — Kobe's deadpan refusal to celebrate being up 2-0 in the Finals. |
| 18 | 2009-06 | **Satisfaction**<br/>*[Article]* | Sports Illustrated | Kobe validates his leadership by winning a championship without Shaquille O'Neal. |
| 19 | 2009-06 | **Jimmy Kimmel Live: Post-Championship Appearance**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/zoskjoqRt0U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | ABC | Kobe celebrates the 2009 championship on Jimmy Kimmel, showing a rare lighter side after achieving his goal. |
| 20 | 2010-06 | **Game 7 Post-Game Interview: 2010 NBA Finals**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/6okxpJ6z9-o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBA TV | Emotional post-game interview after winning back-to-back championships in Game 7 against the Celtics. |
| 21 | 2010-06 | **Kobes Final Challenge**<br/>*[Article]* | Sports Illustrated | SI chronicles the back-to-back championship run that cemented Kobe's all-time legacy. |
| 22 | 2010-08 | **Kobe Bryant sits down with Ahmad Rashad**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/rgY4zylpl54" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBA TV | In-depth sit-down with Ahmad Rashad on leadership, team dynamics, and the championship mentality. |

### Late Career & Retirement (2011–2016)


| # | Date | Title | Source | Summary |
|---|------|-------|--------|---------|
| 23 | 2012-09 | **In Depth with Graham Bensinger**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/yzrYs4tnx1E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | In Depth with Graham Bensinger | Comprehensive 15-part interview covering childhood in Italy, basketball development, family life, mentality, and life philosophy. |
| 24 | 2013-01 | **Kobe Bryants First Tweet**<br/>*[Social]* | Twitter | The story of Kobe's Twitter debut and his 10 most iconic tweets, showing how he adapted to the social media era. |
| 25 | 2013-06 | **Kobe Bryant Up Close Interview**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/ORhcTM80e0A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Jimmy Kimmel Live | Extended interview covering life, legacy, social relationships, and Kobe's evolving public persona during his late career. |
| 26 | 2013-10 | **The Last Alpha Dog**<br/>*[Article]* | Sports Illustrated | Lee Jenkins' seminal profile: 'I have self-doubt. I have insecurity. I have fear of failure... You don't deny it, but you also don't capitulate to it.' |
| 27 | 2014-08 | **Father Time and Kobe Inc.**<br/>*[Article]* | Sports Illustrated | Kobe forms Kobe Inc., inspired by Michael Jackson's pursuit of excellence. 'Just because something evolves, it doesn't make it any less better.' |
| 28 | 2015-02 | **Kobe Bryant and Jimmy Fallon Beer Run Story**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/ZOXo4Z8josI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | The Tonight Show Starring Jimmy Fallon | Kobe tells the hilarious story of his first beer run at age 17, showcasing his storytelling ability and humor. |
| 29 | 2015-02 | **Kobe: The Interview with Ahmad Rashad**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/yVozBmgq2Fk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBA TV | Follow-up interview with Ahmad Rashad on leadership evolution, championship losses, and legacy. |
| 30 | 2015-11 | **Dear Basketball**<br/>*[Article]* | The Players Tribune | Kobe's poetic retirement letter personifying basketball as a lifelong love — later adapted into an Oscar-winning animated short. |
| 31 | 2015-12 | **Kobe Bryant's Muse (Full Documentary)**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/oo13niMuo4k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Showtime | Full Showtime documentary: Kobe's most personal reflections on childhood in Italy, the 2003 legal crisis, the Achilles rupture, and rebuilding his identity. |
| 32 | 2016-04 | **Swan Song**<br/>*[Article]* | Sports Illustrated | SI's farewell coverage of Kobe's final season and 60-point finale. |
| 33 | 2016-04 | **Mamba Out: Farewell Speech and Post-Game Press Conference**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/gOhx_Fv8XTQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | ESPN / NBA | Full farewell speech and post-game presser after scoring 60 in his final game. 'Mamba Out' enters sports history. |
| 34 | 2016-04 | **Post-Retirement Interview on Ellen**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/T0jM37coZPo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | The Ellen DeGeneres Show | Light-hearted post-retirement interview on Ellen about adjusting to civilian life and fatherhood. |
| 35 | 2016-08 | **Kobe Bryant at USC | Mamba Mentality**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/T5-vgyEbtPU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | USC Marshall School of Business | Masterclass at USC on deliberate practice, youth development, the 81-point game preparation, tap-dancing lessons, and mental health in athletics. |
| 36 | 2016-10 | **Kobe Bryant on Business, Investments and Mentality**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/5w4ZA2WmBY0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | WSJDLive | Kobe articulates his corporate philosophy: how basketball's attention to detail transfers directly to analyzing startup business models. |
| 37 | 2016-11 | **Alibaba 11.11 Countdown Gala**<br/>*[Speech]* | Alibaba Group | Kobe's appearance at Alibaba's Singles' Day gala, bridging sports and global commerce. |
| 38 | 2016-12 | **Canvas City: Musecage Discussion**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/w6_5t9tMa3Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | ESPN | Discussion of the 'Musecage' concept — Kobe's custom training facility designed around studying predatory behavior. |

### Post-Retirement & Legacy (2017–2025)


| # | Date | Title | Source | Summary |
|---|------|-------|--------|---------|
| 39 | 2017-03 | **Kobe Bryants 2017 Interview on First Take**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/TAwjRiKY9GI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | ESPN | Kobe reveals studying John Williams' composing process to revolutionize his basketball approach, and discusses the Black Mamba alter ego. |
| 40 | 2017-04 | **Kobe Bryant on Kids Ignoring His Advice**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/0zJh2FMTaDE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | The Tonight Show Starring Jimmy Fallon | Humorous segment about Kobe's daughters ignoring his basketball advice, showing the 'Girl Dad' persona. |
| 41 | 2017-05 | **End of an Era: A Conversation With NBA Great Kobe Bryant**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/5ma2oQfiLF4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Milken Institute Global Conference | Deep conversation with Jim Gray on business, the Shaq dynamic, what 'making teammates better' really means, and finding purpose post-basketball. |
| 42 | 2017-12 | **Jersey Retirement Ceremony Speech**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/juyhKZ20Yso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | NBA / Lakers | Emotional jersey retirement ceremony where Kobe reflects on what legacy truly means beyond championships and statistics. |
| 43 | 2018-01 | **Interview with Jalen Rose on 81-Point Game**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/JRZxscy-uDs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | ESPN | Kobe revisits the 81-point game with Jalen Rose (who guarded him that night), discussing preparation and mentality. |
| 44 | 2018-04 | **Discussing Detail on ESPN+**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/79pCl52iwRk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Get Up (ESPN) | Kobe discusses his ESPN+ show 'Detail' — breaking down current players' performances with obsessive analytical precision. |
| 45 | 2018-07 | **Fantastic Voyage**<br/>*[Article]* | Sports Illustrated | SI covers Kobe's post-basketball ventures: Oscar win, Granity Studios, and applying Mamba Mentality to storytelling. |
| 46 | 2018-08 | **The Rich Eisen Show Interview**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/v3qrnCLDzCA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | The Rich Eisen Show | Wide-ranging interview on leadership, social dynamics, and the transition from competitor to mentor. |
| 47 | 2018-09 | **The School of Greatness Interview**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/XCHlc7dl744" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | The School of Greatness Podcast | The most comprehensive single interview: scoring zero as a child, Tex Winter's film sessions, Pau Gasol's gold medal, defining greatness, storytelling philosophy, and 4am training with Gianna. |
| 48 | 2018-10 | **The Mamba Mentality: How I Play**<br/>*[Book]* | MCD / Macmillan | Kobe's book on preparation and craft mastery — 'to be a better player, you have to prepare, prepare, and prepare some more.' |
| 49 | 2018-10 | **Mamba Mentality Book Tour Interview**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/670K7nuogIc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Access Hollywood | Book tour interview discussing the philosophy behind The Mamba Mentality and the importance of photographic documentation. |
| 50 | 2019-02 | **Anna Faris Is Unqualified**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/J6iRjbjaRcA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Unqualified Podcast | Candid conversation covering vulnerability, masculinity, the Wizenard book series, diversity in animation, and family life. |
| 51 | 2019-03 | **The Wizenard Series and Coaching**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/I8bUKwjQz3o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | The Tonight Show Starring Jimmy Fallon | Kobe discusses coaching youth basketball with a long-term development focus and his Wizenard fantasy book series. |
| 52 | 2019-09 | **Knuckleheads Podcast Appearance**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/hbMbkynzs30" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | The Players Tribune | Deep dive into the 1996 draft, developing his shot repertoire, mentors like Eddie Jones and Gary Payton, and why Jordan shared secrets only with him. |
| 53 | 2019-09 | **On Purpose with Jay Shetty**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/g2cQ2kD6lzs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | On Purpose Podcast | Philosophical interview on unpacking fear, finding purpose, the Hero's Journey, and the Muse Hall of inspirational figures. |
| 54 | 2019-09 | **Kobe Bryant on Shaq Drama & Raising Four Daughters**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/t8eoIKiDTw8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Jimmy Kimmel Live | Kobe addresses the Shaq relationship dynamics, raising four daughters, and coaching Gianna's team. |
| 55 | 2019-10 | **Patrick Bet-David Valuetainment Interview**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/T9GvDekiJ9c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Valuetainment | Perhaps the most revealing interview: the Halloween theme song pregame ritual, Black Mamba as Gladiator's Maximus, Phil Jackson's deliberate wedge strategy, and the fire analogy for playing through injury. |
| 56 | 2020-01 | **All The Smoke Podcast Episode 11**<br/><br/><iframe width="280" height="157" src="https://www.youtube.com/embed/3R3KIyEgCgc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> | Showtime Basketball | One of Kobe's final interviews: coaching Gianna, the Matt Barnes ball-fake story, modern NBA analytics, and the 'long game' of youth development. |
| 57 | 2020-01 | **Final Tweet Congratulating LeBron James**<br/>*[Social]* | Twitter / Instagram | Kobe's final social media post: congratulating LeBron for passing his scoring record. '#33644' |
| 58 | 2020-02 | **Kobe Bryant: An Extraordinary Life**<br/>*[Article]* | ESPN Special Issue | ESPN's 96-page commemorative magazine chronicling Kobe's extraordinary life and career. |

---


## Contributing

We welcome contributions to expand and improve the Mamba Spirit knowledge base. There are **24 sources** still pending manual extraction — your help can make this skill even more comprehensive.

### Adding a New Source

1. **Fork and clone** the repository:
   ```bash
   git clone https://github.com/zobinHuang/kobe.skill.git
   cd kobe.skill
   ```

2. **Create an asset directory** following the naming convention `YYYY-MM_kebab-case-title`:
   ```bash
   mkdir -p assets/2019-05_my-new-source/
   ```

3. **Add the content file** — either `transcript.md` (for video/audio) or `content.md` (for articles), with YAML frontmatter:
   ```markdown
   ---
   title: "Source Title"
   date: 2019-05
   source: "Publication Name"
   type: video_interview
   url: "https://..."
   extraction_method: manual_override
   transcript_quality: manual
   ---

   [Full transcript or article text here]
   ```

4. **Add `meta.json`** with source metadata:
   ```json
   {
     "title": "Source Title",
     "date": "2019-05",
     "source": "Publication Name",
     "type": "video_interview",
     "url": "https://...",
     "interviewer": "Interviewer Name",
     "themes": ["work", "mentality"],
     "extraction_method": "manual_override",
     "transcript_quality": "manual",
     "extraction_status": "success",
     "failure_reason": null
   }
   ```

5. **Update `sources.json`** — add or update the entry for your source.

6. **Submit a PR** with a clear description of the source and why it's valuable.

### Providing Content for Pending Sources

Check `sources.json` for entries with `"extraction_status": "pending_manual"`. The highest-value targets are:

| Priority | Source | Why It Matters |
|----------|--------|----------------|
| High | Letter to My Younger Self | Kobe's financial & family wisdom — iconic Players' Tribune piece |
| High | Memorial Tributes | Jordan, Shaq, Vanessa speeches — emotional capstone |
| High | Oscar Acceptance Speech | Symbolic moment bridging basketball and art |
| Medium | Players' Tribune articles (6) | Kobe's own unfiltered writing (JS-rendered, needs manual copy) |
| Medium | Graham Bensinger (Re-release) | May contain additional segments not in original |
| Low | Streaming content (3 episodes) | CNN/HBO Max docuseries — requires subscriber access |

To contribute content for a pending source, save the text as `assets/<asset_slug>/content.md` (or `transcript.md`) with the frontmatter format above.

### Guidelines

- **No fabricated content.** Only submit real transcripts, articles, or speeches from verifiable sources.
- **Respect copyright.** Transcripts of publicly available interviews and speeches are acceptable. Do not reproduce full copyrighted books or paywalled articles.
- **Audio files are `.gitignore`d.** If your extraction involved Whisper, only commit the resulting `.md` transcript, not the `.mp3`.
- **Keep `meta.json` accurate.** The `extraction_method` field should reflect how the content was obtained (`manual_override`, `web_fetch`, `yt-dlp_auto_sub`, `whisper`, etc.).

---


## License


This skill is provided for educational and research purposes. All source content remains the intellectual property of its respective creators. Transcripts were extracted from publicly available media using automated tools (yt-dlp, OpenAI Whisper) and manual transcription.


---


<div align="center">


*"The most important thing is to try and inspire people so that they can be great in whatever they want to do."*


**— Kobe Bryant (1978–2020)**


</div>

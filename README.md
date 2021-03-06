# Integrating reproducibility into the undergraduate statistics curriculum

This repository contains slides for and any additional resources related to the "Integrating reproducibility into the undergraduate statistics curriculum" talk at JSM 2016 in Chicago, IL.

## Session information

- **When:** Wed, 8/3/2016, 8:30 AM - 10:20 AM
- **Where:** CC-W196c
- **Line up:**
	+ 8:35 AM - Reproducibility for All and Our Love/Hate Relationship with Spreadsheets — [Jennifer Bryan](https://github.com/jennybc), University of British Columbia
	+ 8:55 AM - Steps Toward Reproducible Research — [Karl W. Broman](https://github.com/kbroman), University of Wisconsin - Madison
	+ 9:15 AM - Enough with Trickle-Down Reproducibility: Scientists, Open This Gate! Scientists, Tear Down This Wall! — [Karthik Ram](https://github.com/karthik), University of California at Berkeley
	+ 9:35 AM - Integrating Reproducibility into the Undergraduate Statistics Curriculum — Mine Cetinkaya-Rundel, Duke University
	+ 9:55 AM - Discussant: [Yihui Xie](https://github.com/yihui), RStudio
- **Chair:** [Amelia McNamara](https://github.com/AmeliaMN) (filling in for [Ben Baumer](https://github.com/beanumber))

## Abstract

The issue of reproducibility often comes up in the context of published research and the need to accompany such research with the data, analyses, software/code necessary to recreate the results. As statistics educators who teach data analysis, we should be instilling best practices in students as early as possible. We advocate for teaching data analysis at all levels of the statistics curriculum using a completely reproducible framework so that the new researchers we train have no other workflow than a reproducible one. Additionally, as statisticians we should be marshaling efforts for promoting reproducible data analysis practices in other disciplines as well. While all this might sound like a tall order at first, modern tools for literate programming (e.g. R Markdown) and systems for version control (e.g. GitHub, Open Science Framework) paired with carefully designed curricula that integrate the use of these tools early and often make this goal easier to attain than ever before. In this talk we will share experiences from undergraduate courses and research experiences teaching and practicing reproducible data analysis. We will also discuss collaborative efforts with non-statisticians for developing and promoting the use of a reproducible data analysis protocol.

## Talk outline

- Intro:
	- Two pronged approach to spreading reproducibility:
		+ Convince researchers to change their workflows and adopt reproducible ones
		+ Train new researchers who have no other workflow -- this talk focused on this prong
	- Research / teaching:
		+ Often comes up in the context of published research and the need to accompany such research with the complete data and analyses, including software/code 
		+ Educators who teach data analysis should be instilling best practices in students before they set out to do research
- Share experiences from undergraduate courses that teach data analysis within a reproducibile framework
	+ Intro stat 
		- Toolkit: R + RStudio + R Markdown
		- Address common concern: Can students handle it? Oh yeah! 
			+ Scripting vs. GUI
			+ Scripting + RR tools: In fact, this workflow makes it easier to learn R since 
				- keeps workspace clean, 
				- keeps code organized, 
				- code + output always together, and 
				- syntax highlighting
		- More course info: 
			- Course website: https://www.stat.duke.edu/courses/Spring16/sta101.001/
			- Course materials: https://github.com/mine-cetinkaya-rundel/sta101-s16
	+ Intro data science 
		- Toolkit: R + RStudio + R Markdown + git + Github
		- Address common concern: Can students handle it? Yes, 
			+ But need to make instruction of workflow part of the curriculum 
			- Can't just hope students will figure it out
		- More course info: 
			- Course website: https://www.stat.duke.edu/courses/Fall15/sta112.01/
			- Course materials: https://github.com/mine-cetinkaya-rundel/sta112_f15
	+ Advanced stat computing 
		- Toolkit: R + RStudio + R Markdown + git + Github + Testing / Continuous Integration
		- More info at http://bit.ly/statcomp_jsm2016
		- Lesson: grow toolkit along with the complexity of computation
		- Materials: 
			- Course website: http://www.stat.duke.edu/~cr173/Sta323_Sp16/
			- Course materials: https://github.com/Sta323-Sp16
- 2016/2017 projects: Carry the theme of reproducibility through the entire major with a capstone course and senior thesis that is fully reproducible
	+ Need instructor buy-in
	+ Needs to be part of the assessment
	+ Easily adoptable workflow helps
		- [Karl's Steps 2 RR](http://kbroman.org/steps2rr/)
		- [Project TIER](https://www.haverford.edu/tier) protocol
		- [Reproducible Science Curriculum](https://github.com/Reproducible-Science-Curriculum)
- More comments on toolkit:
	+ R / RStudio: Recommended
	+ But R not necessary: 
		- Any scripting language might work 
		- Even though the overhead in some might be more than others
- Pleasant side-effects:
	+ For instructor: easy Q&A + easy grading
	+ For student: easy collaboration + self promotion











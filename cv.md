# Dinara Dervel

dinaradervel@gmail.com ❖ [@dinaradervel](https://t.me/dinaradervel) ❖ +52 322 328 6333 ❖ 
Puerto-Vallarta, Mexico ❖ [LinkedIn](https://www.linkedin.com/in/dinara-dervel-29b120219/) ❖ [GitHub](https://github.com/DinaraDervel)

## SUMMARY

Frontend Developer with strong attention to detail, experience in JavaScript, React, HTML/CSS/email layout. Confident in building responsive interfaces and working in engineering teams. Background in system analysis and finance helps translate business requirements into clean, maintainable code. Quick to learn new tools and technologies.


## SKILLS

* JavaScript, TypeScript, React.JS, React Hooks, Next.js, HTML5, CSS3, SASS, Bootstrap, BEM, Responsive Design, Git, GitHub, API Integration, Testing and Debugging
* Collaboration and Communication, Continuous Learning, Problem-Solving, Code Quality and Standard

### Code Examples

Task from [Codewars](https://www.codewars.com/kata/51c8e37cee245da6b40000bd)
```javascript
function solution(text, markers) {   
   if (!markers.length) return text.trimEnd();
  const pattern = '\\'+markers.join('|\\');
  const regex_pattern = `(?:${pattern}).*\\n`;
  const regex_pattern_end = `(?:${pattern})[^(?:${pattern})]*$`;
  const regex = new RegExp(regex_pattern, 'gm');
  const regex_end = new RegExp(regex_pattern_end, 'gm');
  do {
    text = text.replaceAll(regex, "\n").split('\n').map(el=>el.trimEnd()).join('\n').replaceAll(regex_end, "");
  } while (!!text.match(regex) || !!text.match(regex_end));
  return text.split('\n').map(el=>el.trimEnd()).join('\n');
}
```

## WORK EXPERIENCE

#### 5D Hub (Dec. 2024 – Present)
*Frontend Developer*
* Built an adaptive marketing website using Next.js
* Integrated dynamic data using the Google Sheets API

#### Project Work (Jan. 2023 – Dec. 2024)
*Frontend Developer*
* Created responsive, semantic web interfaces
* Developed functional components and API-based interactions

#### Centre of Information Technologies (Nov. 2021 – Dec. 2022)
*System Analyst*
* Worked closely with developers and stakeholders
* Wrote clear and structured technical tasks
* Designed over 50 financial message schemes on a proprietary platform


## EDUCATION

#### South Ural State University - June, 2008
*Bachelor in Engineering, Applied Mathematics*

#### South Ural State University - June, 2012
*Bachelor in Economics, Banking*


## ENGLISH LANGUAGE

*English proficiency level - B2*
# 14a - CSS Transforms, Transitions, and Animations

## Transforms
- Transform is a new CSS property that can be used as an alternative way to style HTML elements
- Transform comes with multiple vendor prefixes so that it can be used on all browsers
- Transforms allows for two-dimensional transforms or three-dimensional transforms
- Translate is a value similar to relative positioning that allows an element to be moved without interrupting the normal flow of a document
- Perspective is needed in order to transform an object in 3D. Perspective is similar to a vanishing point and that is how the object is changed from 2D to 3D

## Transitions & Animations
- Transition is new to CSS3 and allows the element to change in appearance from one state to another without the use of flash or javascript
- Animation is new to CSS3 as well. However, unlike transition, Animation allows an element to have multiple points of transition instead of transitioning from one point to another
- These stylings need to know when to occur, so the use of pseudo-classes (:hover, :focus, :active, and :target) is the best way to identify when transitioning should occur
*Example transition CSS*
>.box {
>  background: #2db34a;
>  transition-property: background;
>  transition-duration: 1s;
>  transition-timing-function: linear;
> }
> .box:hover {
>  background: #ff7b29;
> }
- This example CSS would change the background of the box element when it hovers over and the transition occurs over 1 second (https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
- vendor prefix should be added to transitions and animations to ensure that they are supported on all browsers
- transition-property can be used to target certain properties within an element, otherwise, all will be targeted
- transition properties can be applied to most CSS styling such as border-color, font-size, color, etc
- @keyframes is used for animations and it is where a user will set multiple breakpoints for a transition. This is required when transitioning is from more than two points
- animations need a name and duration in order to function. Delay and timing-function can also be added to animations
- iterations can be used to determine how many times an animation shall occur and they are allowed to occur an infinite amount of times

# 14b - What Google Learned From Its Quest to Build the Perfect Team
    The article begins by discussing Julia Rozovsky's experiences during her time at Yale in which she worked in two different groups. One of the groups was mandatory and everyone in the group had a similar background, while the other group was voluntary and everyone in the group had a unique background. Julia explained how working with the first group was not a good experience and working with the second group was a great experience and easy-going. The main focus of the article is about working with groups and how Google set out to research what groups within their organization were the most efficient and why they were the most efficient.
    
    
    This research project was referred to as Project Aristotle. The research initially could not find any patterns on what teams were most successful. In fact, their research determined the "who" of the group was irrelevant. Eventually, the research team determined that "group norms" made the biggest difference in a team's success. Group norms describe how teams handle conflict or how the team interacts with each other, whether those interactions be encouraging or discouraging. In other words, a team's success is highly dependent on how well everyone within the group treats each other.
    
    
    Additionally, a group of psychologists from M.I.T. also performed a study on people working in teams. How well the team interacted with each other was determined to be far more important than the intelligence of individual members, or the leadership structure of each group. Two behavior that successful groups shared is that these groups had an equal distribution of conversational turn-taking, meaning that everyone in the group took turns speaking roughly the same amount. The second trait these groups shared is that they all had "average social sensitivity, meaning that they understood verbal and non-verbal cues that expressed how one was feeling. The Google research team finally determined psychological safety is important for a team to be most successful. Psychological safety means that members of a group feel safe within a group and that they will not be ridiculed, embarrassed, or rejected for speaking up or presenting an idea.
    
    
    Once the research was concluded, the team had to find a way to implement psychological safety in the workplace which would not be an easy task. The group was approached by Matt Sakaguchi who was a former SWAT member and was not a "tech person", but was successful at managing teams. He did, however, work with a group that did not "gel" together and he wanted to be more successful in the future. The team presented him with a social norm survey to present to his workers. The survey showed troubles existed within the group, but after they had a meeting where people discussed something personal about themselves (Sakaguchi had stage 4 cancer), they found it easy to discuss the survey results and new norms. 

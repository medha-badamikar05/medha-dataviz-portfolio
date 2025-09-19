| [home page](README.md) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# MAKEOVER MONDAY - HIGH STREET COFFEE CAFFEINE CONTENT

## Step one: the visualization

[High street coffee compared](https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S)

[Selected data viz](high-street-original.png)

As a coffee enthusiast, I was naturally intrigued by an article exploring caffeine content across different beverages. The accompanying visualization initially appeared attractive — cleanly laid out in a table format, with a sense of organization. However, I found it difficult to extract insights at a glance. It lacked the intuitive clarity and comparative utility — ranking low on the spectrum of effective visual communication, especially when evaluated through the lens of Stephen Few’s principles - majorly intuitiveness and engagement. 
It involved some cognitive gymnastics (ref Good Charts text Chapter 2); going back and forth through the numbers. Using a table with caffeine values without graphical hierarchy forces the viewer to manually compare digits — which is slow and error-prone. 
Most critically, the visualization lacked a clear narrative thread — the very element that drew me to it in the first place. Without a guiding message or insight, the chart becomes a static display of data, rather than a meaningful tool for discovery, which is why I decided to redesign this visualization. 


## Step two: the critique
### What Worked Well:
*	The visualization is clean and uncluttered.
*	The consistent use of just three colors (blue, black, and white) adds to the simplicity and visual appeal.
*	The title is aligned with the table’s purpose and stands out with bold styling.
*	The coffee cup icons add an aesthetic touch that connects well with the theme.
*	The legend is clear and intuitive, requiring no extra effort to interpret.
*	(A personal note: the coffee imagery resonates well, perhaps because data feels more engaging when tied to something relatable like coffee.)
### What Didn’t Work Well:
*	The numeric values appear scattered without any visible pattern (e.g., increasing or decreasing), which reduces readability.
*	The drink size in brackets is redundant—this detail could instead be conveyed once in the table header.
*	The chart doesn’t enable quick comparisons or highlight key takeaways at first glance.
*	While the title introduces the subject, it doesn’t guide the reader toward a story or insight, leaving them to interpret the data on their own.
*	The use of “n/a” is ambiguous and may mislead readers into thinking certain drinks lack caffeine altogether, which undermines the chart’s purpose.

The main audience for this visualization is anyone who buys coffee from high-street coffee chains such as Costa and Starbucks. It’s relevant to because everyone would want to know how much caffeine they consume through drinks purchased at these chains. This data warns customers of overconsumption of caffeine. 
While the current visualization presents the information in a structured table, it is not very effective at telling a clear story because:
*	The table cells contain too many numbers, which can overwhelm the viewer.
*	The data is not organized in descending order of caffeine content, making comparisons difficult.
*	The numbers are shown only as text, without visual encoding through shapes or colors, which would make the information quicker and easier to understand.
  
## Step three: Sketch a solution
In my redesign sketch, I would start by removing redundant details, such as the drink sizes in brackets, to keep the visualization clean and easy to read. My next focus would be on improving clarity by sorting the data and emphasizing the most relevant comparisons. For example, it would be useful to highlight that Costa Coffee consistently offers drinks with higher caffeine content than Starbucks, and ensure this stands out clearly in the visualization.

I’m also excited to experiment with visual encodings that go beyond plain numbers. One idea is to use coffee cup icons whose size or fill level corresponds to the amount of caffeine in each drink. This would provide a more intuitive, engaging way for viewers to grasp differences at a glance. At the same time, I’m considering more conventional approaches such as bar charts, which are excellent for side-by-side comparisons between vendors and drink types.

Following are the initial versions (sketches drawn by hand) of my redesign 
* [Sketch1 - use of cups](high-street-coffee-v1.jpg)
  The goal was to give viewers a clear and intuitive understanding of the data. To achieve this, I used uniform cup icons and filled each one with a proportionate amount of red color to visually represent the caffeine content (in mg) on a relative scale
* [Sketch2 - hand sketched bar graph](high-street-coffee-v2.jpg)
 I wasn’t fully convinced by the cup-based sketch, as the scale lacked precision and could lead to misinterpretation of the actual values. As a result, I decided to explore a more traditional bar chart approach, which offered greater accuracy and clarity.

The bar graph looked really neat, so I tried to use grouped bar graph next. I decided to get feedback at this point.
* [Final bar graph - Datawrapper](redesign_bar_1.png)

## Step four: Test the solution

Questions to ask: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 


| Question | Interview 1 | Interview 2 | Interview 3| 
|----------|-------------|-------------|------------|
|Can you tell me what you think this is?          |  They asked me what Costa Coffee was :(         |  It compares caffeine content across 5 different coffee chains✅           | Comparison of caffeine content
| Is there anything you find surprising or confusing?         |     This looks like a Yes/No type of bar graph        |      The grey colour doesn't add meaning - doesn't associate with caffeine       | The grey colour dismisses the single shot espresso category  |
| Who do you think is the intended audience for this?        |    Coffee lovers         |   People monitoring their coffee intake          | Anyone who drinks coffee |
| How long did you take to understand what this visualization is about? | More than 30 seconds | 15 seconds | More than 30 seconds |

Synthesis: 
After interviewing 3–4 peers, I took time to reflect on their feedback and identified a few recurring themes:
* The usage of grey colour was a primary concern, which almost everyone found unappealing or ineffective. As a result, I decided to eliminate grey from the visual palette.
* The time required to interpret the graph was another key issue. Viewers found it difficult to quickly grasp the insights, prompting me to rethink the design for improved clarity and faster comprehension.

* I experimented with a grouped bar chart in Excel (image below) using high-contrast colors, but ultimately chose not to pursue this approach. The colors appeared too bright and visually overwhelming, which distracted from the main narrative rather than supporting it
* [Excel viz](redesign_bar_2.png)
  
Upon further thought and consideration, I also made the decision to narrow the focus of the visualization. Instead of comparing both Single Shot Espresso and Cappuccino, I chose to highlight just Cappuccino. This allowed me to better emphasize the central insight — that Costa Coffee's Cappuccino has a caffeine-to-drink-size ratio of 0.92, which is exceptionally high for a single cappuccino and worth drawing attention to.

## Step five: build the solution

To elevate clarity and visual appeal, I constructed a bar chart using a range of brown hues to create a natural association with coffee. I added a reference line to indicate the recommended daily safe limit for caffeine intake (from the article), helping viewers contextualize the values. The bars were sorted to support quick comparison, and I used a darker shade within the same color palette to highlight Costa Coffee, drawing attention to its significance. Additionally, I included a label on the highlighted bar to display the exact caffeine content, reinforcing the key takeaway visually and numerically.

<div class='tableauPlaceholder' id='viz1758239219555' style='position: relative'>
<noscript>
<a href='#'><img alt='COSTA CAPPUCINO CAFFEINE CONTENT HIGHEST ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;Caffeine_cont&#47;Costa_coffee_bar_Chart&#47;1_rss.png' style='border: none' /></a></noscript>
<object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
<param name='embed_code_version' value='3' /> <param name='site_root' value='' />
<param name='name' value='Caffeine_cont&#47;Costa_coffee_bar_Chart' />
<param name='tabs' value='no' /><param name='toolbar' value='yes' />
<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;Caffeine_cont&#47;Costa_coffee_bar_Chart&#47;1.png' /> <param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />
<param name='display_spinner' value='yes' />
<param name='display_overlay' value='yes' /><param name='display_count' value='yes' />
<param name='language' value='en-US' />
<param name='filter' value='publish=yes' />
</object>
</div>           
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1758239219555');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## References
Good charts : the HBR guide to making smarter, more persuasive data visualizations  Scott Berinato: Chapter 2 (When the chart hits our eyes)

## AI acknowledgements
I used AI (Claude AI) to review my redesign and it responded as follows:

Looking at this horizontal bar chart, here's what I see:

**What it is:** This appears to be a comparison of caffeine content in cappuccinos from different coffee chains, with Costa having dramatically higher caffeine levels than the others.

**What it's telling me:** Costa cappuccinos contain roughly 320-330mg of caffeine, which is more than double any other chain shown. Greggs and Pret are in the middle range (around 180-200mg), while Caffè Nero and Starbucks have significantly lower caffeine content (around 100-120mg).

**What I find surprising/confusing:**
- Costa's caffeine level seems extremely high - that's approaching the daily recommended limit in a single drink
- The massive gap between Costa and everyone else makes me wonder if there's a measurement error or if Costa uses a very different brewing method/bean type
- No error bars or methodology explanation

**Intended audience:** Likely health-conscious consumers, coffee enthusiasts, or people who need to monitor caffeine intake for medical reasons. Could also be for regulatory/consumer advocacy purposes.

**What I'd change:**
- Add methodology notes (how was this measured? same cup sizes?)
- Include confidence intervals or sample sizes
- Consider adding a reference line for daily recommended caffeine limits
- Maybe add the actual numerical values on the bars
- Verify Costa's number - it's so dramatically different it raises questions about data accuracy


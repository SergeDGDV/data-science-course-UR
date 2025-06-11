# SQL, Python & NLP for User Research Team
## Introduction & Motivation

As the voice of the player inside Paradox Interactive, the User Research team plays a critical role in shaping our games. From surveys and user testing to review analysis and sentiment tracking, your work is essential to helping designers, producers, and leadership understand how players feel, behave, and respond to what we build.
But as the scale and complexity of our data grows, so too does the need to move beyond surface-level analysis.
This course path is designed to help you go deeper—to give you the tools, confidence, and practical skills to handle the data yourself, analyze it in new ways, and extract richer, more actionable insights. From structured survey data to unstructured open-ended feedback, from SQL queries to text analysis in Python, this training enables you to take control of the entire research pipeline.

You don’t need a technical background. You don’t need to be a developer. What you do need is the willingness to get hands-on with the data—because the tools are now accessible, and the value they offer is enormous.

By the end of this training, you’ll be able to:
* Extract structured and unstructured data directly using SQL
* Clean and transform data using Python and Pandas
* Perform statistical summaries and generate visualizations
* Analyze player sentiment using NLP libraries like VADER and TextBlob
* Generate word clouds, key phrase extractions, and theme clustering
* Present findings in compelling, evidence-based formats for game teams and stakeholders

This course is all about  interpreting, exploring, and surfacing insights that help game teams move forward with confidence. This training is not just a course—it’s an investment in your own capability and in the future of Paradox’s player-first development culture.

## Overview
## Course A: Essential SQL for User Researchers
The objective is to quickly get you up to speed with SQL basics so you can extract and manipulate data needed for research projects.
### Detailed Session Breakdown (4 Sessions)

#### Session 1: Databases 101
```Topics Covered```: Tables, rows, columns, ```SELECT```, ```WHERE```, ```LIMIT``` (<b>Duration</b>: 90 minutes)
* What is SQL, what is a database, and why it matters in research
* Table structure demo using example review dataset (columns, types, keys)
* Writing simple ```SELECT``` statements + ```WHERE``` filters
* Using ```LIMIT``` to preview small datasets
* Practice queries: Retrieve all reviews for a specific game.

#### Session 2: Aggregating & Filtering
```Topics Covered```: ```COUNT```, ```AVG```, ```GROUP BY```, ```HAVING``` (<b>Duration</b>: 90 minutes)
* Quick recap of ```SELECT/WHERE```
* Intro to ```COUNT```, ```AVG```, ```MIN```, ```MAX``` – use in reviewing player feedback
* ```GROUP BY```: Segmenting by region, platform, language
* ```HAVING```: Filtering aggregated results
* Mini-challenge: What games receive the most positive sentiment by region?


#### Session 3: Combining Data
```Topics Covered```: Understanding JOINs (```INNER JOIN```, ```LEFT JOIN```) (<b>Duration</b>: 90 minutes)
* Visual explanation of how JOINs work
* ```INNER JOIN```: Link reviews to user segments
* ```LEFT JOIN```: Ensure you keep full review list while joining metadata
* Practice exercise: Join review text with game and platform metadata


#### Session 4: Practical Application
```Topics Covered```: Real-world scenarios using reviews and structured data (<b>Duration</b>: 90 minutes)
* Recap key SQL patterns and joins
* Case Study: Pull and group reviews mentioning technical issues for a specific title
* Build a SQL query to support a real research request (individualized) and present results


## Course B: Introduction to Python & Data Science for User Research
The objective is to provide practical skills in Python to analyze structured and unstructured data, with an emphasis on sentiment analysis, visualization, and natural language understanding.

### Detailed Session Breakdown (15 Sessions)

#### Session 1: Python for Research
Topics: What is Python, installing Anaconda, using Jupyter
Time
Activity
0–30 min
Setup: Install Anaconda, create first Jupyter notebook
30–60 min
Basic Python syntax: variables, lists, functions
60–90 min
Load a CSV using Pandas and display contents


#### Session 2: Data Cleaning
```Topics```: Handling missing data, converting types, string cleaning
| 0–30 min | Drop/fill missing data in review dataset using .dropna() and .fillna() | | 30–60 min | Convert datatypes (e.g., to datetime or numeric) | | 60–90 min | Standardize text (lowercasing, remove punctuation) using .str methods |

#### Session 3: Exploratory Data Analysis
```Topics```: Summary statistics, value counts, detecting outliers
| 0–30 min | Use .describe() and .value_counts() | | 30–60 min | IQR-based outlier detection | | 60–90 min | Histogram and boxplot visualizations to explore distribution of review length |

#### Session 4: Data Visualization
```Topics```: Seaborn, Matplotlib, styling plots
| 0–30 min | Line plot, bar chart, countplot | | 30–60 min | Customize with titles, axis labels | | 60–90 min | Visualize average rating by DLC or sentiment over time |

#### Session 5: Aggregating Data
```Topics```: Groupby, pivot tables, cross-tabulation
| 0–30 min | Use .groupby() for aggregated review stats | | 30–60 min | Create a pivot table showing average sentiment per language | | 60–90 min | Crosstab feedback frequency by sentiment category |

#### Session 6: Text Handling in Python
```Topics```: Tokenization, string processing, stopwords
| 0–30 min | Basic NLP pipeline: tokenization using nltk or spaCy | | 30–60 min | Removing stopwords and symbols | | 60–90 min | Count most common words across all reviews |

#### Session 7: NLP Basics
```Topics```: Sentiment with TextBlob/VADER, text preprocessing
| 0–30 min | Apply VADER to sample reviews | | 30–60 min | Analyze polarity scores and interpret thresholds | | 60–90 min | Segment reviews into positive, neutral, and negative groups |

#### Session 8: Sentiment in Feedback
```Topics```: Apply sentiment across datasets
| 0–30 min | Apply sentiment scoring on full dataset | | 30–60 min | Aggregate sentiment by game or platform | | 60–90 min | Compare trends pre- and post-patch (temporal sentiment change) |

#### Session 9: Word Clouds & Visualization
```Topics```: Word frequency, n-grams, visual presentation
| 0–30 min | Generate basic word cloud | | 30–60 min | Visualize most common 2- and 3-word phrases | | 60–90 min | Compare word clouds between different sentiment groups |

#### Session 10: Extracting Key Phrases
```Topics```: TF-IDF, theme identification
| 0–30 min | Use TfidfVectorizer to extract key phrases | | 30–60 min | Compare top phrases between DLCs or player segments | | 60–90 min | Phrase filtering for relevance and actionability |

#### Session 11: Survey Analysis Techniques
```Topics```: Likert scale, open-text summarization
| 0–30 min | Handle 1–5 scales using .mean() and .mode() | | 30–60 min | Visualize scale distribution per question | | 60–90 min | Sentiment + scoring merge: compare written and scored feedback |

#### Session 12: SQL to Python Pipeline
```Topics```: Query from SQL, analyze in Python
| 0–30 min | Use sqlalchemy or pymysql to run a query from Python | | 30–60 min | Load result into Pandas | | 60–90 min | Clean, summarize, and visualize imported data |

#### Session 13: Exporting Results
```Topics```: CSV, Excel, Dashboards
| 0–30 min | Export final results using df.to_csv() or df.to_excel() | | 30–60 min | Create simple reporting table or visual summary | | 60–90 min | Use insights to create stakeholder-ready insights (brief slide format or document) |

#### Session 14: Advanced NLP (Optional)
```Topics```: Topic modeling (LDA), clustering
| 0–30 min | Intro to topic modeling, what LDA does | | 30–60 min | Run topic modeling on player reviews | | 60–90 min | Label clusters and compare across products |

#### Session 15: Final Case Study
```Topics```: Full feedback analysis
| 0–30 min | Choose a game, define research question | | 30–60 min | Apply full pipeline: SQL → Python → sentiment/key phrases | | 60–90 min | Present findings as a 2-slide summary for internal stakeholders |

## Delivery Format
* <b>Length</b>: Weekly 90-minute sessions (flexible for longer workshops)
* <b>Style</b>: Highly interactive with live demonstrations and collaborative exercises
* <b>Tools</b>: Jupyter Notebooks, Python (Anaconda), SQL editor, VADER/TextBlob/NLTK
* <b>Materials</b>: Clean sample datasets (Steam reviews, survey exports), code notebooks, cheat sheets
* <b>Support</b>: Access to internal channel for Q&A and shared resources








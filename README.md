# Resume-Matching-with-Job-Descriptions-Using-PDF-CVs


## PDF Data Extraction
- Download the Kaggle "resume dataset."
- Run the PDF extractor script to extract details from CVs in PDF format.
- Key details extracted include:
  - Category (job role)
  - Skills
  - Education (degree, institution)

## Job Description Data Understanding
- Use the Hugging Face datasets library to fetch job descriptions.
- Consider extracting 10 job descriptions.

## Candidate-Job Matching
- Tokenize and preprocess job descriptions and extracted CV details.
- Convert the tokenized text into embeddings using a pretrained model like DistilBERT from Hugging Face.
- Calculate cosine similarity between job descriptions and CVs.
- Rank CVs based on similarity scores.

# Data Sources
- Kaggle Resume Dataset ([link](https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset))
- Hugging Face Job Descriptions Dataset ([link](https://huggingface.co/datasets/jacob-hugging-face/job-descriptions/viewer/default/train?row=0))

# Methodology
- PDF extraction with PyPDF2 or PDFMiner.
- Text tokenization and embedding using DistilBERT from Hugging Face.
- Cosine similarity calculation for candidate-job matching.
# Challenges
- "One of the primary challenges encountered during this project was developing a robust PDF extractor that could consistently and accurately extract key details such as job roles, skills, and education information from a variety of resume PDF formats, which often differed in structure and layout."
- Processing a large number of resumes and job descriptions efficiently to provide timely matching results can be resource-intensive.
# Contact
- kumarmurugantamil@gmail.com

# Results
- the top 5 candidates for each job description based on the highest similarity scores.
- The final output = 
- Company Name: Google
Job Description: minimum qualifications
bachelors degree or equivalent practical experience years of experience in saas or productivity tools businessexperience managing enterprise accounts with sales cycles
preferred qualifications
 years of experience building strategic business partnerships with enterprise customersability to work through and with a reseller ecosystem to scale the businessability to plan pitch and execute a territory business strategyability to build relationships and to deliver results in a crossfunctionalmatrixed environmentability to identify crosspromoting and uppromoting opportunities within the existing account baseexcellent account management writtenverbal communication strategic and analyticalthinking skills
about the job
as a member of the google cloud team you inspire leading companies schools and government agencies to work smarter with google tools like google workspace search and chrome you advocate the innovative power of our products to make organizations more productive collaborative and mobile your guiding light is doing whats right for the customer you will meet customers exactly where they are at and provide them the best solutions for innovation using your passion for google products you help spread the magic of google to organizations around the world
the google workspace team helps customers transform and evolve their business through the use of googles productivity collaboration and content management suite of applications as part of an entrepreneurial team in this growing business you will help shape the future of businesses use technology to connect with customers employees and partners
as a google workspace sales specialist you will be responsible for maintenance and expansion of google workspace business growth across the region with customers in this role youll create and execute the strategy and provide unique insights on applying google workspace solutions to enterprisesyou will build an excellent pipeline and work with the account teams to build out the customer solution and establish partnerships you will strategize with partners to increase account and territory business growth you will work directly with customers coordinate internal resources and construct successful strategies at account and territory level
google cloud accelerates organizations ability to digitally transform their business with the best infrastructure platform industry solutions and expertise we deliver enterprisegrade solutions that leverage googles cuttingedge technology  all on the cleanest cloud in the industry customers in more than  countries and territories turn to google cloud as their trusted partner to enable growth and solve their most critical business problems
Top Resume 1: Similarity Score = 0.9500117301940918
File Name: /content/data/data/CONSULTANT/51724595.pdf


Top Resume 2: Similarity Score = 0.9417224526405334
File Name: /content/data/data/BANKING/11773925.pdf


Top Resume 3: Similarity Score = 0.9323586225509644
File Name: /content/data/data/INFORMATION-TECHNOLOGY/32959732.pdf


Top Resume 4: Similarity Score = 0.9314501285552979
File Name: /content/data/data/ADVOCATE/91051945.pdf


Top Resume 5: Similarity Score = 0.9310486912727356
File Name: /content/data/data/ARTS/21867728.pdf


--------------------------------------------------
Company Name: Apple
Job Description: description
as an asc you will be highly influential in growing mind and market share of apple products while building longterm relationships with those who share your passion 
customer experiences are driven through you and your partner team growing in an ever changing and challenging environment you strive for perfection whether its maintaining visual merchandising or helping to grow and develop your partner team

qualifications
a passion to help people understand how apple products can enrich their livesexcellent communication skills allowing you to be as comfortable in front of a small group as you are speaking with individuals years preferred working in a dynamic sales andor results driven environment as well as proven success developing customer loyaltyability to encourage a partner team and grow apple business
Top Resume 1: Similarity Score = 0.9526113271713257
File Name: /content/data/data/DIGITAL-MEDIA/16276121.pdf


Top Resume 2: Similarity Score = 0.9450546503067017
File Name: /content/data/data/BUSINESS-DEVELOPMENT/67501448.pdf


Top Resume 3: Similarity Score = 0.9265621900558472
File Name: /content/data/data/BPO/24727739.pdf


Top Resume 4: Similarity Score = 0.926356852054596
File Name: /content/data/data/TEACHER/12587973.pdf


Top Resume 5: Similarity Score = 0.9241980314254761
File Name: /content/data/data/ENGINEERING/36149549.pdf


--------------------------------------------------
Company Name: Netflix
Job Description: its an amazing time to be joining netflix as we continue to transform entertainment globally netflix is the worlds leading internet entertainment service with over  million paid memberships in over  countries enjoying tv series documentaries and feature films across a wide variety of genres and languages members can watch as much as they want anytime anywhere on any internetconnected screen members can play pause and resume watching all without commercials or commitments

the consumer products team aspires to connect members to our content and each other by bringing their favorite stories to real life our products and campaigns should entertain delight and bring joy to our fans all over the world 

due to the expansion of licensees and categories we are in need of additional support with active and prospective partnerships for current and upcoming titles we are looking for a licensing coordinator who will work across the entire slate of netflix content to bring our content to life via compelling products they will support two managers who oversee the food and beverage toys and collectibles electronics and sporting goods categories focusing on us and canada regional opportunities the individual would be a taskmaster extraordinaire who will assist in the day to day deliverables working alongside internal as well as external partners the successful candidate will be a dynamic professional who has an understanding of the outbound licensing workflow and can roll up their sleeves to knock out tasks in an orderly and swift pace 

key responsibilities
help drive business by supporting licensing managers on tasks related to category management facilitating information between external and internal stakeholders and maintaining communication of product and partner planscoordinate with internal teams to gather and distribute brand and marketing updates to share out with licensing partnersmaintain and update title strategies with category licensing plans and activitycollaborate with licensing partners to obtain placement updates and distribute to internal business partnersassist licensing managers with compiling licensing recaps following product launches schedule meetings and when needed draft and distribute meeting recaps to respective business partnersprepare distribute and track deal memos and final agreements to ensure deals are processed efficiently through all stepswork with licensing managers to prepare onboarding for new licenseesfacilitate receipt of forecasts and send royalty payment reminders as neededpartner with creative teams to keep product development on track to attain commercial objectives
what we need from you
demonstrated  years of experience in preferably outbound licensing functionunderstanding of category manufacturing and sales cycle for toys andor food and beverage is preferredexperience working with reputable entertainment andor lifestyle brandsselfstarter motivated proactive and flexibleability to thrive under pressure in a fastpaced dynamic environmentpossess attention to details with superb organizational skillsmultitasker extraordinaire with ability to prioritizeexcellent communicator alignment with our company culture and values
Top Resume 1: Similarity Score = 0.9407306909561157
File Name: /content/data/data/BANKING/11773925.pdf


Top Resume 2: Similarity Score = 0.9390230178833008
File Name: /content/data/data/FITNESS/10235429.pdf


Top Resume 3: Similarity Score = 0.9369084239006042
File Name: /content/data/data/ARTS/24349611.pdf


Top Resume 4: Similarity Score = 0.9359490871429443
File Name: /content/data/data/CONSTRUCTION/22983516.pdf


Top Resume 5: Similarity Score = 0.9357219338417053
File Name: /content/data/data/DIGITAL-MEDIA/25723793.pdf


--------------------------------------------------
Company Name: Robert Half
Job Description: description

web designers looking to expand your professional reach welcome to robert half marketing  creative start the process with robert half today

we are searching for highly skilled web designers with experience working within corporate brand standards and guidelines the ideal candidates would have advanced skills in creating wireframes designing mobile applications landing pages interactive sites qa testing experience working with various interfaces and familiarity with uxui design principles candidates are expected to have strong skills in adobe photoshop illustrator and indesign any experience in html css and javascript is a major plus familiarity with content management systems is highly preferred

there is nothing more satisfying when looking for freelance and fulltime creative opportunities than working with someone who knows your area of expertise as industry professionals robert half marketing  creative is a team that puts your needs first and effectively represents you as a creative talent thats the kind of service youll receive from our team at robert half

we have marketing advertising and creative backgrounds just like yours  so were on your side right from the start could you ask for a better support team

requirements
  years experience in a web design role
 experience working within a clients brand standards or guidelines
 advanced skill in the adobe creative cloud

innovation starts with people

robert half is the worlds first and largest specialized talent solutions firm that connects highly qualified job seekers to opportunities at great companies we offer contract temporary and permanent placement solutions for finance and accounting technology marketing and creative legal and administrative and customer support roles

robert half puts you in the best position to succeed by advocating on your behalf and promoting you to employers we provide access to top jobs competitive compensation and benefits and free online training stay on top of every opportunity  even on the go

questions call your local office at  robert half will consider qualified applicants with criminal histories in a manner consistent with the requirements of the san francisco fair chance ordinance all applicants applying for us job openings must be legally authorized to work in the united states benefits are available to temporary professionals visit

  robert half an equal opportunity employer mfdisabilityveterans by clicking apply now youre agreeing to
Top Resume 1: Similarity Score = 0.941325843334198
File Name: /content/data/data/TEACHER/37660306.pdf


Top Resume 2: Similarity Score = 0.9397023320198059
File Name: /content/data/data/CONSTRUCTION/22983516.pdf


Top Resume 3: Similarity Score = 0.9375391602516174
File Name: /content/data/data/ADVOCATE/35474904.pdf


Top Resume 4: Similarity Score = 0.9358228445053101
File Name: /content/data/data/CONSULTANT/51724595.pdf


Top Resume 5: Similarity Score = 0.9312170147895813
File Name: /content/data/data/SALES/25810233.pdf


--------------------------------------------------
Company Name: TrackFive
Job Description: at trackfive weve got big goals were on a mission to revolutionize recruiting with easytouse tools and platforms and we envision a future where we can fill every open job with a qualified candidate thats why were looking for pioneerspeople who blaze trails and are committed to doing great work we might be small but we are mightyweve got more than a decade of skin in the game yet weve managed to maintain our startup feel the trackfive culture is centered around hard work but we believe strongly in balance and having funin a nutshell we love coming to work we value different backgrounds and perspectives believing that together we can use our creativity and curiosity to make amazing things happen

if youre ready to be a part of something exciting trackfive is currently searching for a talented web developer this position is not dependent on location and can be local to the office with hybrid or inoffice options available or fully remote
 please note that a skills test may be a requirement for potential candidates in the interview process

what youll do

the web developer is responsible for delivering robust solutions to our clients they work collaboratively to support trackfives existing web application portfolio and the successful delivery of new development initiatives

the life of a trackfive web developer
 contribute to all phases of the development lifecycle by following internal procedures and coding standards
 build  layouts from provided psd files
 build dynamic web apps using phpmysqlframeworks
 leverage rest services and other thirdparty apis
 rapidly solve problems bugs and compatibility issues
 troubleshoot test and maintain the core product software and databases to ensure strong optimization and functionality
 develop and deploy new features to facilitate related procedures and tools as necessary

skills necessary
  years or experience with html and csssass
  years of experience with programming php applications and lamp stack development
 experience with   javascript and jquery
 thorough understanding of relational databases and security relating to phpmysql
 expert knowledge with content management systems either from your own design or from mvc frameworks such as zend laravel etc
 ability to build and consume custom soap and rest apis
  years of experience writing unit testsdetailing procedures
 selfmotivated requiring minimal supervision
 exceptional organization and communication skills

why you want to work at trackfive
 free health insurance for employees with no waiting period
 dental and vision insurance trackfive splits the cost with you
 your birthday is a paid holiday
 companypaid short and longterm disability insurance
 companypaid life insurance
 flex time
 paid parental leave
 companymatched retirement plan with no waiting or vesting period
 the opportunity to workfromhome a few days a week
 so much swag
 cool inoffice perks like free snacks massages yoga and bringyourpettowork days just to name a few
 the opportunity to work with a great group of people up to some very exciting things
 the opportunity to attend our epic annual holiday party
 trackfive is an equal opportunity employer
Top Resume 1: Similarity Score = 0.9486981630325317
File Name: /content/data/data/CONSULTANT/51724595.pdf


Top Resume 2: Similarity Score = 0.9400691986083984
File Name: /content/data/data/CONSTRUCTION/22983516.pdf


Top Resume 3: Similarity Score = 0.9339760541915894
File Name: /content/data/data/TEACHER/37660306.pdf


Top Resume 4: Similarity Score = 0.9323346614837646
File Name: /content/data/data/DIGITAL-MEDIA/14761906.pdf


Top Resume 5: Similarity Score = 0.932170033454895
File Name: /content/data/data/ACCOUNTANT/28939941.pdf


--------------------------------------------------
Company Name: DesignUps
Job Description: designups is a nashville based design and interactive agency at designups we have a strong focus on elevating brands with our expertise in design and customer experience

are you a frontend developer with a serious interest in design and ui this could be a great fit if so this job is for someone in the greater nashville area the majority of the work can be done remotely but we do require some time in our east nashville office location hey its not too bad to walk to five points pizza or wildcow for lunch

this is a contract position to start with a competitive hourly rate we would like to find the right person to join our team for a longterm role

skills needed
strong attention to design details typography ui etc
translating designs responsively for multiple screen sizes
familiarity with bootstrap or other similar frameworks
wordpress knowledge and desire to learn is a major bonus
Top Resume 1: Similarity Score = 0.9293685555458069
File Name: /content/data/data/SALES/33236701.pdf


Top Resume 2: Similarity Score = 0.9236233234405518
File Name: /content/data/data/DESIGNER/39252859.pdf


Top Resume 3: Similarity Score = 0.9233429431915283
File Name: /content/data/data/ARTS/79432080.pdf


Top Resume 4: Similarity Score = 0.9194503426551819
File Name: /content/data/data/ARTS/34146825.pdf


Top Resume 5: Similarity Score = 0.9184271097183228
File Name: /content/data/data/CHEF/10889157.pdf


--------------------------------------------------
Company Name: Equisolve, Inc.
Job Description: about the position

the web designer is responsible for providing designrelated support for clientrelated and internal projects

additionally the web designer is responsible for providing designrelated support for projects that are currently in development client review and postlaunch when assigned

daytoday
 collaborate closely with design managers on websiterelated projects including finishing projects that have a set art direction to hand over to the development team
 work crossfunctionally with content and development teams which includes facilitating design discussions and adjusting existing designswebsites based on client feedback in preparation for the launch of their sites
 partner with development teams to ensure the implementation of your designs and user experiences are of the highest quality
 use and evolve our design systemlibrary to craft sketches flows prototypes and highfidelity visuals for client websites and product features
 work closely with design leadership to inform and improve our processes identifying opportunities for elevating our product and user experience
 provide designrelated support for postlaunch projects

requirements

our ideal candidate
 is detailoriented has an excellent eye for detail and enjoys delivering pixelperfect and welldocumented designs
 knows how to design websites has experience working with and understanding responsive design patterns and systems
 is prepared to take the baton and run gladly takes on projects with set art direction and finishes off remaining design production work
 has design system experience has experience working with scalable design systems within an inhouse design team
 is a team contributor more than willing to work with design managers to develop the strategy and rationale for features and improvements to internal processes
 can speak up and be understood has strong verbal and written communication skills which is a must for a remote company
 can adjust and pivot can navigate and move forward quickly within a fastscaling company and an everevolving creator website tool
 is hungry to improve gladly welcome feedback on their own performance from design managers along with nondesigners with the intent of professional growth in the company
 most importantly can joke around a sense of humor is a must in our company

our company culture revolves around among other things working hard and laughing harder

requirements
  years of experience as an individual contributor on a web or product design team for desktop and mobile
 an excellent portfolio showcasing a strong foundation in typography interaction and visual design and ideation

bonus props for personal projects that display your design aesthetic and passions
 solid understanding of building usable accessible ada and modular design systems that can scale

bonus props for certification in or related to ada
 experience facilitating the adoption of visual design andor patterns across a design project
 excellent understanding of figma and other design tools
 excellent written and verbal communication skills and ability to clearly communicate design decisions
 strong organizational skills and a selfstarter

benefits
 remote always
 generous pto
 allowance for continuing education or training
 shiny new gear of your choice apple products
 medical dental longterm and short term disability insurance
 companysponsored life insurance

dont meet  of the qualifications above thats okay apply anyway 
Top Resume 1: Similarity Score = 0.9472206830978394
File Name: /content/data/data/CONSTRUCTION/22983516.pdf


Top Resume 2: Similarity Score = 0.945604681968689
File Name: /content/data/data/BANKING/11773925.pdf


Top Resume 3: Similarity Score = 0.9444919228553772
File Name: /content/data/data/BUSINESS-DEVELOPMENT/10501991.pdf


Top Resume 4: Similarity Score = 0.9431468844413757
File Name: /content/data/data/ARTS/24349611.pdf


Top Resume 5: Similarity Score = 0.9430150985717773
File Name: /content/data/data/CONSULTANT/51724595.pdf


--------------------------------------------------
Company Name: Zander Insurance Agency
Job Description: job description

zander insurance group is one of the largest direct marketers of insurance and identity theft solutions services in america our company was founded more than  years ago with the mission to protect families today millions of visitors browse our websites they are a vital way we acquire communicate with and keep our clients

the web designer will drive revenue growth through the design and optimization of all clientfacing zander web properties

the ideal candidate is comfortable working with highlevel stakeholders and they understand the importance of getting projects done efficiently most importantly the web designer enjoys working and as a result has a positive attitude that contributes to the overall health of the zander culture we are seeking a contributor who thrives while working autonomously asks questions when necessary and problem solves daily

this is a fulltime position and includes a competitive salary and comprehensive benefits this position reports directly to the evp of marketing and will be based in our nashville tennessee office with opportunities to work remotely

responsibilities include
 designing compelling direct response websites and digital content that supports the zander brand campaign objectives and drives measurable actions
 utilizing knowledge of zander products and services to create designs that support an action or campaign goal
 creating designs that are compatible across multiple devices and screen sizes
 creating mockups to conceptualize designs and presenting ideas to stakeholders
 continually improving the existing user experiences and in the process driving revenue growth
 preproduction image optimization and preparation
 work with key stakeholders to ensure appropriate review and approvals for all clientfacing sites

the ideal candidate
  years of digital design experience driving online sales or marketing
 has the ability to communicate effectively with highlevel clients
 thrives in a fastpaced and teamoriented environment
 is open to new ideas and able to adapt to changes quickly
  years of experience with
 adobe creative suite including photoshop illustrator and indesign
 sketch
 has solid experience with ui wireframing
 has a strong ability to articulate the why when presenting design concepts
 htmlcss and js experience preferred but not required

what we have to offer
 potential to work from home
 monthly profits distributions
 health and dental insurance paid  by zander insurance
  dollarfordollar matching on your k
 generous paid time off

we are an equal opportunity employer applicants are considered for position and are evaluated without regard to mental or physical disability race religion sexual orientation color gender national origin age marital status military or veteran status or any other protected local state or federal status unrelated to the performance of the work involved
Top Resume 1: Similarity Score = 0.9506679177284241
File Name: /content/data/data/CONSTRUCTION/22983516.pdf


Top Resume 2: Similarity Score = 0.9505645632743835
File Name: /content/data/data/CONSULTANT/51724595.pdf


Top Resume 3: Similarity Score = 0.9469582438468933
File Name: /content/data/data/TEACHER/37660306.pdf


Top Resume 4: Similarity Score = 0.9447012543678284
File Name: /content/data/data/DIGITAL-MEDIA/25723793.pdf


Top Resume 5: Similarity Score = 0.9441259503364563
File Name: /content/data/data/BANKING/11773925.pdf


--------------------------------------------------
Company Name: Tuff
Job Description: tuff is a growth marketing team working with clients to drive growth by creating managing measuring and optimizing highperforming user acquisition campaigns were a fully remote and small team with endless opportunities for autonomy ownership and impact

we work with clients in nearly every industry and a typical engagement with tuff includes paid search social ads seo content strategy creative and cro every account has a dedicated growth marketing lead and is supported by various channel experts

for this position we are looking for an experienced web designer to join our cro team you will be the third web designer joining the team  the cro team also includes a conversion rate optimization specialist and ux copywriter

in this role you will work on designs in figma for existing website optimizations and landing page development across  different client accounts this could include testing out different ctas remediating the homepage or other core pages adding in new landing pages refining pricing pages updating user flows redesigning blogs and more

requirements

about you
 you are a skilled web designer who has the flexibility and understanding to work on multiple established brands at once with quick mockup design turnarounds and have a strong understanding of how your designs will be translated in the web build process
 you have  years of experience managing quickturnaround designdevelopment projects in various cms platforms webflow wordpress shopify contentful etc and landing page buildings unbounce and leadpages for startups and scaleups
 you have strong project management skills setting up and adhering to detailed production timelines following up with team members to get what you need and organizing creative assets for developers
 you have a clean aesthetic and a sharp eye for layout color and typography
 youre a strategic thinker and understand how to design digital website experiences that are compelling you have a passion for brand building and can help push user experience forward across all digital touchpoints
 youre curious and solutionoriented and enjoy finding new and innovative design solutions you can work independently but are keen to collaborate across disciplines with developers cro and ux copy to design fresh website experiences

during month  youll
 shadow tuffs cro team lead on three existing tuff clients to learn more about their individual brands and ongoing cro and web design needs
 adopt our existing development and design process by working with our existing web designers lyn and arturo
 learn how to guide and own website project priorities timelines scopes and costs within the tuff process using teamwork and slack
 design at least one website optimization and landing page for  different clients

during months    youll
 work on various website designs ongoing monthly improvements for five tuff clients this includes testing out different ctas remediating the homepage or other core pages adding in new landing pages refining pricing pages updating user flows redesigning blogs and more
 work with growth marketers and the cro team at tuff as well as content and creative to implement website designs and updates for clients
 manage one to three developer contractorsfreelancers who will be responsible for implementing your designs on our clients sites
 fully guide website project priorities timelines scopes and costs within the tuff process

things can change quickly at tuff this breakdown isnt prescriptive but intended to give you a better sense of the role

benefits

about you
 you have  years of experience as a web designer with a background working on sites for companies in various industries
 you have experience working with a creative production team and a familiarity with creative production tools mainly figma and adobe suite
 you have an inclusive handson collaboration style with proven experience clearly communicating timelines and deliverables
 you have a learning mindset you are committed to getting better every day
 you have a bias toward action and are both efficient and adaptable
 you are a driver focused on making an impact on the organization and clients every day
 you have demonstrated success testing and uncovering useful insights and sharing them in an engaging form that inspires people to take action

benefits

we are a passionate team of thirty distributed across the us

youll work closely with the whole team in particular with elle creative strategist lyn web designer arturo web designer and kristin sr growth marketer coo to get up to speed on current clients and iterate on the cro and web design process at tuff

 fully remote  work from anywhere you want

 comprehensive health vision and dental coverage

 k with matching

 unlimited pto policy  and we encourage you to take it

 parental leave   paid  weeks

 home office or coworking space stipend

 month internet reimbursement

 continuing training stipend of  annually

 wellness day every quarter

 annual team retreats

the starting salary range for this role is   we use a compensation formula that adjusts for experience

applicants must be based in the us
Top Resume 1: Similarity Score = 0.9469282627105713
File Name: /content/data/data/CONSULTANT/51724595.pdf


Top Resume 2: Similarity Score = 0.9432533383369446
File Name: /content/data/data/BANKING/11773925.pdf


Top Resume 3: Similarity Score = 0.9410988092422485
File Name: /content/data/data/SALES/25810233.pdf


Top Resume 4: Similarity Score = 0.9401098489761353
File Name: /content/data/data/BUSINESS-DEVELOPMENT/10501991.pdf


Top Resume 5: Similarity Score = 0.940065324306488
File Name: /content/data/data/CONSTRUCTION/22983516.pdf


--------------------------------------------------
Company Name: General Dynamics Information Technology
Job Description: type of requisition regular

clearance level must be able to obtain none

job family web design

gdit has over  years of experience supporting the technology science and mission of the environmental protection agency gdit technologists scientists and innovators are experts in moving applications to the cloud modeling massive data sets in highperformance computing environments supporting innovative and bleeding edge technologies and scientific initiatives defending the cyber landscape and driving automation

highlevel skills
 htmlcssjavascript
 drupal 
 section  compliance expertise pertaining to pdfs adobe acrobat pro videos interactive trainings websites and web applications jaws dragon zoomtext articulate
 graphics design adobe photoshop illustrator after effects and lightroom

specific tasks
 designs and builds complex graphics page layouts and animation that suit web pages and enhance its layout to create visual appeal
 creates an advanced detailed draft of the website outlining the various web pages according to client specifications and needs
 provides thorough testing to ensure the website is userfriendly and interactive
 provides thorough review of the final webpage design for the next level production
 collaborates with other web professionals and provide guidance on the implementation of the website
 stays current with the latest design software to improve in knowledge and skills and be able to create better design quality
 provides guidance and leadership to lessexperienced web designer personnel

desired qualifications 

babs or equivalent experience  years of experience

additional job description

covid vaccination gdit does not have a vaccination mandate applicable to all employees to protect the health and safety of its employees and to comply with customer requirements however gdit may require employees in certain positions to be fully vaccinated against covid vaccination requirements will depend on the status of the federal contractor mandate and customer site requirements

we are gdit the people supporting some of the most complex government defense and intelligence projects across the country we deliver bringing the expertise needed to understand and advance critical missions we transform shifting the ways clients invest in integrate and innovate technology solutions we ensure today is safe and tomorrow is smarter we are there on the ground beside our clients in the lab and everywhere in between offering the technology transformations strategy and mission services needed to get the job done

gdit is an equal opportunityaffirmative action employer all qualified applicants will receive consideration for employment without regard to race color religion sex sexual orientation gender identity national origin disability or veteran status or any other protected class

covid vaccination gdit does not have a vaccination mandate applicable to all employees to protect the health and safety of its employees and to comply with customer requirements however gdit may require employees in certain positions to be fully vaccinated against covid vaccination requirements will depend on the status of the federal contractor mandate and customer site requirements

we are gdit the people supporting some of the most complex government defense and intelligence projects across the country we deliver bringing the expertise needed to understand and advance critical missions we transform shifting the ways clients invest in integrate and innovate technology solutions we ensure today is safe and tomorrow is smarter we are there on the ground beside our clients in the lab and everywhere in between offering the technology transformations strategy and mission services needed to get the job done

gdit is an equal opportunityaffirmative action employer all qualified applicants will receive consideration for employment without regard to race color religion sex sexual orientation gender identity national origin disability or veteran status or any other protected class
Top Resume 1: Similarity Score = 0.9514603614807129
File Name: /content/data/data/INFORMATION-TECHNOLOGY/30223363.pdf


Top Resume 2: Similarity Score = 0.9472149014472961
File Name: /content/data/data/ARTS/24349611.pdf


Top Resume 3: Similarity Score = 0.9433370232582092
File Name: /content/data/data/ADVOCATE/49486820.pdf


Top Resume 4: Similarity Score = 0.9431358575820923
File Name: /content/data/data/ARTS/21867728.pdf


Top Resume 5: Similarity Score = 0.9429662227630615
File Name: /content/data/data/HEALTHCARE/37001381.pdf


--------------------------------------------------



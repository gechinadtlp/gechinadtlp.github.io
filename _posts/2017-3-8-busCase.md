---
layout: post
title:  "Business Case"
date:   2017-03-08 13:50:39
categories: others
---
## GE Power Digital Case Study

### Business Background
 

GE works to build, cure, move and power the world. Made up of ten major divisions, GE engineers world-class industrial products and services. One of the largest divisions is GE Power, a tier-one business that generated $30B of revenue in 2015.


![GE Businesses](/static/img/GEBusinesses.png)


GE Power is a world leader in power generation with deep domain expertise that helps customers deliver electricity from a wide spectrum of fuel sources. We are transforming the electricity industry with the digital power plant, the world’s largest & most efficient gas turbine, full balance of plant solutions, and our data-leveraging software. Our innovative technologies and digital offerings help make power and water more affordable, reliable, accessible and sustainable.
Today, GE technology delivers 1/3 of the world’s electricity and each day we add enough power to support 100,000 people. GE is leading the digital transformation of the energy industry by turning your existing power plant into a virtual copy known as a “digital twin”.
GE Power offers a diverse range of products through their sub-businesses: Gas Power Systems, Steam Power Systems, Nuclear, Water/Distributed Power, and Power Services. Through close customer collaboration, Power Services dedicates itself to providing service solutions for the products we sell (e.g. gas/steam turbines). We deliver tailored solutions across total plant assets and their operational lifetime to help customers achieve productive business outcomes. Power Services has capabilities and expertise to service and support 90+ original equipment manufacturer (OEM) brands in 150+ countries. By keeping customers at the center of everything we do, our team helps them identify new revenue opportunities, lower operating costs and implement flexible technologies.

### Predix Background
GE Digital offers a complete portfolio of products, solutions and services that help leading industrial enterprises drive digital transformation. At the heart of this portfolio is Predix – the platform for the Industrial Internet. Purpose-built for industry, it empowers organizations to develop, deploy, and operate industrial apps—driving outcomes such as reduced unplanned downtime, improved asset output, and greater operational efficiency. Decades of experience in industries from power generation to manufacturing to healthcare have enabled GE to create a platform that meets the unique needs of industry.
Predix is a cloud-based platform that runs in a cloud managed by GE. By leveraging a core set of services and infrastructure provided by the platform, companies can build a system-wide view of their assets. This view allows both improved optimization of each part in the system as well as optimization of the entire system. This is the unique “edge-to-cloud” coverage offered by the Predix platform.
As a leader in the industrial world, GE built a cloud that meets the needs industrial companies have for scale, security, and regulatory compliance. Predix cloud can handle vast amounts of Industrial Internet information, while also managing customer SLAs, security, support, governance, compliance, and export


controls. 

At a high level, the primary components of Predix are:
•	Predix Machine: Predix Machine is the software layer responsible for communicating with the industrial asset and the Predix Cloud, as well as running local applications, like edge analytics. This component can be installed on gateways, industrial controllers and sensors.
•	Predix Services: Predix provides industrial services that developers can use to build, test, and run Industrial Internet applications. It also provides a microservices marketplace where developers can publish their own services as well as consume services from third parties. Operational Services enables application developers to manage the lifecycle and commercialization of their applications.
•	Predix Cloud: The Predix Cloud is a global secure cloud infrastructure that is optimized for industrial workloads and meeting regulatory needs.

### Case Background


Combined Cycle Power Plant is a typical solution offered by GE Power. Normally, it combines with 4 systems: gas cycle system, steam cycle system, electric system, control system. Key assets include gas turbine, steam turbine and generator. Preventative maintenance and efficiency optimization are two typical operations in power plant daily work. 

Preventative Maintenance: An outage occurs when the product (i.e. a turbine) stops operating as usual. There are two types of outages – planned and unplanned. When an unplanned outage comes, it means a huge loss of power plant and a disaster for the society. Preventative maintenance, as a kind of planned outage, occurs when the customer decides to stop running the turbine in advance and perform regular service.
Efficiency Optimization requires high flexibility of power plant assets. Usually, the demand of electricity varies over month, which means it would be a waste if assets are running at 100% productivity all the time. Also, outage during a peak time will cause huge loss to both power plant and the society. A balance between supply and demand is necessary to power plants.

In this case, you're the operations leader of a large combined cycle power plant in China. You're building a Digital Twin for your plant, to better understand its daily operation, perform preventative maintenance, and optimize the efficiency of its power generation. You use Predix to simulate the plant model. Based on Predix provided services, you are required to propose a digital power plant solution, including but not limited to below items.
#### 	What problems you want to address in your solution and what’s the business impact?
#### 	What kind of industrial services or applications you want to build for your power plant?
#### 	what's the architecture for building such an industrial solution in Predix?
##### • How to connect key assets in power plant based on Predix?
##### • What are the key KPIs of your power plant and where does the data come from?
##### • What type of data visualization can best present the data or analysis results?
Final deliverable is accepted with a detailed solution in PowerPoint format. 

### More Reference: 
[GE Official][geofficial]

[GE Power][gepower]

[GE Digital][gedigital]

[Predix Official][predix]

[Predix工业互联网白皮书.pdf][iiot]

[geofficial]: http://www.ge.com/cn/ 
[gepower]: http://pgchina.ge.com.cn/ 
[gedigital]: https://www.ge.com/digital/ 
[predix]: https://www.predix.io/ 
[iiot]: http://newsroom.ge.com.cn/sites/newsroom.ge.com.cn/files/Predix工业互联网白皮书.pdf 

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help

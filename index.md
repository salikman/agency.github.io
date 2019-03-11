---
layout: default
---
<div id="blog" class="section md-padding bg-grey">
		<!-- Container -->
		<div class="container">
			<!-- Row -->
			<div class="row">
				<!-- Section header -->
				<div class="section-header text-center">
					<h2 class="title">Recents news</h2>
				</div>
				<!-- /Section header -->
				<!-- blog -->
				{% for post in site.posts %}
				<div class="col-md-4">
					<div class="blog">
						<div class="blog-img">
							<img class="img-responsive" src="" alt="">
						</div>
						<div class="blog-content">
							<ul class="blog-meta">
								<li><i class="fa fa-user"></i>{{ post.author }}</li>
								<li><i class="fa fa-clock-o"></i>{{ post.date | date: "%-d %B" }}</li>
								<li><i class="fa fa-comments"></i></li>
							</ul>
							<h3>{{ post.title }}</h3>
							<p></p>
							<a href="{{ post.url }}">Read more</a>
						</div>
					</div>
				</div>
				{% endfor %}
				<!-- /blog -->
			</div>
			<!-- /Row -->
		</div>
		<!-- /Container -->
	</div>

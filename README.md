<p align="center">
	<h1 align="center"><b>Automod</b></h1>
<p align="center">
    Automatically detect and fix deprecated code patterns in pull requests using codemods.
</p>
<br/>
</p>

Automod watches your repository for pull requests that update dependencies. When it detects a version change that introduces breaking or deprecated APIs, it runs relevant codemods and suggests fixes directly in the PR. without merging or modifying code unless you approve.

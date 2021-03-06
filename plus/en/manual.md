---
layout: default
ident: manual
lang: en
title: Manual
---

<div style="position: relative;" align="center">
<p style="font-size: 40px;">Reference Guide</p>
</div>

<div class="plus">

	Here you have a short reference guide for users and collaborators <br><br>

	<b>Using Mathifold</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		Structure of the webpage
		</div>

		<div class="dissap">
		The webpage has a tree-like structure with four levels:

		<ul style="list-style-type: none;">
		<li>-Topics (e.g. Geometry)</li>
		<li>-Subjects (e.g. Classical Geometry)</li>
		<li>-Chapters (e.g. Triangles)</li>
		<li>-Posts (e.g. Definition Centroid)</li>
		</ul>

		<b>Posts</b> contain small amounts of theoretical content.
		</div>
	</div>

	<div>
		<div class="bcgreen boxdissap">
		Types of posts
		</div>

		<div class="dissap">
		The <b>posts</b> may be of the following types

		<table style="width:90%">
  			<tr>
    			<td><img src="/images/symb/exposition.svg"></td>
    			<td><b>exposition</b></td>
    			<td>These are the first introductory approaches to a subject and consist of some motivation and intuitive concepts, informal definitions and the meaning of theorems</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/definition.svg"></td>
    			<td><b>definition</b></td>
    			<td>Define concepts in a formal fashion</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/theorem.svg"></td>
    			<td><b>theorem</b></td>
    			<td>State and proof the most important results on which mathematical developments are built</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/lemma.svg"></td>
    			<td><b>lemma</b></td>
    			<td>These are auxiliary results which, not having the specific weight of a theorem, are important for their subsequent proof</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/corollary.svg"></td>
    			<td><b>corollary</b></td>
    			<td>These are logical consequences following from a theorem</td>
  			</tr>
            <tr>
                <td><img src="/images/symb/calculation.svg"></td>
                <td><b>calculation</b></td>
                <td>Symbolic developments which should be stressed among the other ones</td>
            </tr>
  			<tr>
    			<td><img src="/images/symb/example.svg"></td>
    			<td><b>example</b></td>
    			<td>Make concrete the theory shown before, thus providing experience, making learning stronger and giving rise to concepts on which next developments are based</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/visualisation.svg"></td>
    			<td><b>visualisation</b></td>
    			<td>Provide visual support for the theory (as pictures or videos)</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/applet.svg"></td>
    			<td><b>applet</b></td>
    			<td>Complement theoretical developments with interactive elements</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/remark.svg"></td>
    			<td><b>remark</b></td>
    			<td>Deal with subtle concepts which may give rise to confusion along the main train of thought</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/counterexample.svg"></td>
    			<td><b>counterexample</b></td>
    			<td>Show that some implication is not correct by establishing an example where it does not apply</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/problem.svg"></td>
    			<td><b>problem</b></td>
    			<td>Put the acquired knowledge to the test thus building the learning process upon a solid basis</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/biography.svg"></td>
    			<td><b>biography</b></td>
    			<td>Sketch the impact that a particular person had in the history and development of Mathematics</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/quotation.svg"></td>
    			<td><b>quotation</b></td>
    			<td>Collect quotations or historical texts reflecting the spirit of Mathematics</td>
  			</tr>
  			<tr>
    			<td><img src="/images/symb/unfinished.svg"></td>
    			<td><b>unfinished</b></td>
    			<td>These are unfinished posts, whose existence is however needed for the network of concept interconnections</td>
  			</tr>
		</table>

		</div>
	</div><br>

	<b>Construction</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		GitHub
		</div>

		<div class="dissap">
		The files that build the webpage are located in the repository <b>beta_mathifold</b> in GitHub: <a href="https://github.com/jxm-math/beta_mathifold" target="_blank">https://github.com/jxm-math/beta_mathifold</a>. In this way, all the content is open-source. GitHub also provides a suitable platform to manage the different contributions.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Jekyll
		</div>

		<div class="dissap">
		Mathifold is built by the static site generator <a href="https://jekyllrb.com/" target="_blank">Jekyll</a>. People interested in collaborating in the development of the webpage should have some knowledge of it.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Navigation file
		</div>

		<div class="dissap">
		The Navigation file shows the tree of contents up to the first three levels: topics, subjects and chapters. It is located in <a href="https://github.com/jxm-math/beta_mathifold/blob/master/_data/nav.yml" target="_blank">/data/nav.yml</a>. Each chapter has an identifier 'ident' which is used to match the posts correctly.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Posts
		</div>

		<div class="dissap">
		The posts are located in the folder <a href="https://github.com/jxm-math/beta_mathifold/tree/master/_posts" target="_blank">/_posts</a> and are  separated by language. Each post is a <b>.md (markdown)</b> file named 'yyyy-mm-dd-name-of-the-file.md'. This file has a head, like a 'data sheet', and after that the content itself. In the data sheet the following items must be filled:

		<ul style="list-style-type: none;">
		<li>-<b>title</b>: Title of the post</li>
		<li>-<b>lang</b> and <b>category</b>: both the code of the language of the post</li>
		<li>-<b>permalink</b>: code-of-the-language/ident</li>
		<li>-<b>ident</b>: an identifier that must be different for each post and that should synthesize its content. It usually starts with the type of the post.</li>
		<li>-<b>parent</b>: the identifier of the chapter to which the post belongs, according to the Navigation file.</li>
		<li>-<b>kind</b>: the code of the kind of post.</li>
		<li>-<b>mathjax</b>: 'true' or 'false' according to whether the page needs mathjax (LaTeX for HTML).</li>
		<li>-<b>layout</b> and <b>type</b>: both filled with 'post'.</li>
		</ul>

		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Multimedia
		</div>

		<div class="dissap">
		To introduce pictures or videos, they must be located in the folder '/images/images', and if having the source code, this must be located with the same name (though different extension) in '/images/codes'. Then complete the post with the following command: <br><br>

		{% raw %}

		{% resource name-of-the-file.xxx %}

		{% endraw %}<br><br>

		and automatically the picture or video will appear in the webpage.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Links
		</div>

		<div class="dissap">
		To cite another post, introduce the command<br><br>

		{% raw %}

		{% cite identifier %}

		{% endraw %}<br><br>

		where 'identifier' is the 'ident' (inside the 'data sheet') of the post we want to cite.
		</div>
	</div><br>

	<b>Softwares used in Mathifold</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		Geogebra
		</div>

		<div class="dissap">
		<div style="
		background-color: lightgreen;
    	width: 80%;
    	border: 0px;
    	padding: 25px;
    	margin: 0 auto;">
    	GeoGebra is dynamic Mathematics software for all levels of education that brings together geometry, algebra, spreadsheets, graphing, statistics and calculus in one easy-to-use package. GeoGebra is a rapidly expanding community of millions of users located in just about every country. GeoGebra has become the leading provider of dynamic mathematics software, supporting science, technology, engineering and mathematics (STEM) education and innovations in teaching and learning worldwide.</div>

    	<a href="https://www.geogebra.org" target="_blank">Geogebra</a> is the software we are using for applets. We are very grateful to Geogebra Team for allowing us to use their product in Mathifold and we hope our webpage will also be an efficient broadcasting medium for this valuable tool.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		IPE Drawing Editor
		</div>

		<div class="dissap">
		<div style="
		background-color: lightgreen;
    	width: 80%;
    	border: 0px;
    	padding: 25px;
    	margin: 0 auto;">
    	Ipe is a drawing editor for creating figures in PDF or (encapsulated) Postscript format. It supports making small figures for inclusion into LaTeX-documents as well as making multi-page PDF presentations that can be shown on-line with Acrobat Reader.</div>
    	<a href="http://ipe.otfried.org/" target="_blank">IPE Drawing Editor</a> is the software used for most of the pictures.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Blender
		</div>

		<div class="dissap">
		<div style="
		background-color: lightgreen;
    	width: 80%;
    	border: 0px;
    	padding: 25px;
    	margin: 0 auto;">
    	Blender is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline—modeling, rigging, animation, simulation, rendering, compositing and motion tracking, even video editing and game creation. Advanced users employ Blender’s API for Python scripting to customize the application and write specialized tools; often these are included in Blender’s future releases. Blender is well suited to individuals and small studios who benefit from its unified pipeline and responsive development process. </div>

    	<a href="https://www.blender.org" target="_blank">Blender</a> is a strong bet we make in Mathifold: a powerful software for animated films and applets with high pedagogical value.
		</div>
	</div><br>

	<b>How to collaborate</b> <br><br>

	<div>
		<div class="bcgreen boxdissap">
		Creation of posts and new materials
		</div>

		<div class="dissap">
		In these first stages of the project it is recommendable to <b>directly contact Mathifold's Team before creating materials</b>. <br><br>

		For those having a clear idea of where and how to collaborate, the most appropriate way is by creating a GitHub account, <b>make a fork in repository jxm-math/beta_mathifold</b>, add here the new files and <b>send pull-requests on a periodic basis</b>. It is important for the time being <b>not to modify other files</b> since otherwise pull-requests will have a conflict with files and will not be accepted.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Translation
		</div>

		<div class="dissap">
		The webpage is multilingual and we would like to have it translated to several languages, in such a way that it can help a larger amount of people.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Difussion
		</div>

		<div class="dissap">
		Difussion in <b>social networks and educational centers</b>, in order to get more users and collaborators.
		</div>
	</div>
	<div>
		<div class="bcgreen boxdissap">
		Programming and Design
		</div>

		<div class="dissap">
		We are on the way to set a team of computer specialists which will improve the webpage over the time. As of now, the main challenge is to provide <b>user accounts</b> allowing each student to customize his/her own learning process.
		</div>
	</div><br>


</div>
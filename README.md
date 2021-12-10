# Can BioArt be Simulated?

Kimberly Davis

### Abstract

This paper examines the use of artificial intelligence to create BioArt. In terms of using artificial intelligence to create virtual cells that move and react like real living cells. As a way to mimic the behavior of the cells.
BioArt is a form of art that is more than often created with the use of living tissues, organisms, and bacteria. This practice sometimes leads people to question how ethical this form of art is, while others view this type of art as a new way of viewing life. However, what if there was a way to create BioArt without the use of living components? There is already a wide range of knowledge and databases around biology and the molecular structure of the human body. Given what we know and what information is available, what if artificial intelligence could use this information to mimic the behavior of human cells? Would it then be possible to predict specific reactions? This research paper explores this idea by looking at the different forms of BioArt, what role artificial intelligence can play in creating a more artificial form of BioArt, and taking a look at human cells and examining their basic structure to understand how they function.
Focusing primarily on sickle cells, this research will demonstrate this idea of simulated cells through an interactive BioArt visualization, which will show the effect that sickle cells can have on the blood. Moreover, showing the potential of what could be created, analyzed, or researched through this form of artificial biology.

### Keywords 
BioArt, Artificial Life, Cells, Sickle Cell, Artificial Intelligence

### Introduction

BioArt is a form of art in which artists create art using living components such as tissues, organisms, DNA, and bacteria. This form of art is often produced in laboratories and art studios using biotechnology tools. BioArt has been seen to bridge biology and art together to give a deeper understanding and appreciation of life. As Simou et al. state, “BioArt searches for the meaning of human existence in relation to the natural environment and enhances the value of parts of the human body as autonomous and interdependent subsets.” (Simou et al., 2013, p.690) However, in some cases, concerns have been raised about the ethics of using living species and biotechnology tools. At the same time, many bioartist use BioArt to promote awareness about the moral and ethical concerns around the rights of other living creatures. Many bioartist “are playfully manipulating DNA of species (plants, bacteria, in some cases animals) more for aesthetic ends that ethico-political concerns. The manipulation of the human genome being the most egregious act possible.” (Jagodzinski, 2020, p. 272) This discussion of bioethics is something that many have and continue to debate about what is acceptable.
Nonetheless, most people still view BioArt as a new way of viewing life and bringing together science and art. However, what if there was a way to create BioArt without the use of living components? Would it still have the same effect as traditional BioArt? Consider the use of cells as art as an example. Bioartis have been able to create art by manipulating living cells by changing various biological factors and introducing new cells. To a certain extent, some of the work done by bioartist could be accomplished without using living cells but instead through the use of “simulated cells.”

### Simulated Cells

The study of cells has been around for centuries, creating a global understanding of cell behavior and molecular structures. While there is undoubtedly more information that is still yet to be discovered, the knowledge about cells that are already known is more than enough to create a system of simulated cells that can mimic basic behaviors. The University of Connecticut Health Center developed a concept similar to this. They developed a computer software called Virtual Cell (VCell), “a general software system that allows biologists with little training in physics and mathematics to engage in computational cell biology.” (Loew & Schaff, 2001, p. 401) With this idea of virtual simulations of cells, what if this could create a different form of BioArt? Such as having a system that could create and manipulate cells not entirely for scientific purposes but also for artistic works.
Artificial life art does this by creating softwares that imitate certain aspects of biology. Developed in the early 1990s, “artificial genetics and mutations allowed the viewer to interact with stereoscopic creatures and ecosystems.” (Backman, 2008) In addition, it is stated in the article The past, present, and future of artificial life that “ALife attempts to synthesize properties of living systems in computers, machines, and molecules. Thus, ALife aims to understand biological life better by creating systems with life-like properties and developing novel forms of life”. (Aguilar et al., 2014) This leads to say that artificial life is essentially the answer to creating simulated cells for the use of creating BioArt. However, it does not appear that this form of BioArt is being utilized to its fullest potential in creating artificial life art that entirely focuses on the data of real biology.

Figure 1. Popularity of different themes per year, as measured by papers published in the Artificial Life journal.

Figure 1 shows a chart created to showcase the popularity of different themes of papers published in the Artificial Life Journal between 1993 - 2014. The theme of Computational Biology had been reasonably steady throughout the years; however, the theme of art has not been as well represented in the journal. This is likely because many artists may prefer to showcase their work in different areas. (Aguilar et al., 2014) However, this chart at least shows that using simulated cells (A-Life) that focus more on the data of real biology as a means for creating art is worth exploring further.
Therefore, by creating cells that mimic the behaviors and functions of natural living cells. This paper explores this idea by creating a BioArt visualization of cells interacting, focusing on blood cells which are some of the most critical cells in the human body. While also showcasing the effects that Sickle Cell can have on the blood.

### Sickle Cell

Sickle cell is a genetic blood disorder that affects hemoglobin, the molecule in red blood cells that supplies oxygen throughout the body. Sickle Cells are red blood cells that are underdeveloped due to a lack of hemoglobin in the blood. Normal red blood cells have a circular shape, while sickled cells have a crescent shape, as shown in figure 2. A person with sickle cell would have a mix of both normal red blood cells and sickle cells. Sickle cells usually only live for 10 to 20 days, while normal red blood cells live for approximately 120 days. This short lifespan of sickle cells can cause anemia, weakening the body. Sickle cells have a sticky, inflexible, and rigid structure, causing them to get stuck in small blood vessels, leading to a lack of blood flow and oxygen to various parts of the body, ultimately causing pain.

Figure 2. Showcasing the difference between normal red blood cells and sickle cells.
Image credit: Genome Research Limited

### Implementation of The Project

Focusing on the characteristics of Sickle Cell, this project demonstrates in an abstract format how blood flows through the body of a person with sickle cell. This project uses a reactive machine type of artificial intelligence to create and control red blood cells based on fundamental characteristics and data of the cells. With the use of Max/MSP software to create the simulation and control the manipulation of the cells. Characteristics such as size, shape, lifespan, and functions are programmed into each simulated cell. See figure 3. 

Figure 3. Showing the 3d modeled red blood cell and sickle cell used for the simulation.
	
At the first stage of testing, these cells are then added to the simulation based on the information gathered and spawned into a “blood vessel” placed on the screen. A force is added into the “blood vessel” to help mimic blood flow. This force pushes the cells through the vessel at various speeds, causing them to flow and create their interactions. The “blood vessel” appearance is not shown and instead kept transparent. See figure 4.

Figure 4. The simulation of the cells in the “blood vessel.”

At the second stage of testing, instead of keeping the cells in “blood vessels,” I decided to experiment with having the cells flow freely. Adding randomly placed forces to make the cells flow around the screen created an expected but exciting interaction between the normal red blood cells and the sickle cells. See figure 5.

Figure 5. The simulation of the cells moving freely around the screen.

In addition, to make this visualization interactive, users can alter the simulation by changing specific values such as the number of cells, colors, force level, and distortion level. These factors can create a noticeable change in the visualization.

### Results

This project is a visualization of simulated cells that show blood cells flowing through a blood vessel and another simulation of them flowing freely. With the addition of sickle cells, the simulation then shows blockages caused by the sickle cells themselves (Fig. 2.). Keeping in mind that this project is meant to be more artistic rather than scientific, the results show that BioArt can be simulated. By showing the biological functions of blood cells in this art form, this project demonstrates the ideas of BioArt. In the sense of creating something that bridges both science and art and showcasing blood cells in a way that would not normally be seen.

### Future work

This project and research is still a work in progress, and as such, there is more work to be done; this includes:

* Further exploring different forms of artificial life art and BioArt and examining how they are created. In order to find ways that this project and the research behind it can be improved.
* Further research into different cells and their functions to expand this project further.
* Continuing to explore the effect of having the cells in “blood vessels” randomly distributed and intertwined on the screen. With the possibility of the user being able to change the structure and distribution of the “blood vessels.”
* The inclusion of other types of cells, such as other blood cells and human cells, as well as mixing other cells that would not typically be found together, such as blood and plant cells.

### Conclusion

While this project might not be helpful for actual scientific work/research, this project shows the possibility of a simulated approach to BioArt. That also bridges onto the use of artificial life as a means to create art. Furthermore, while this would not replace more traditional forms of BioArt, this is at least a suitable alternative/addition to what BioArt could be. 



### References

Aguilar, W., Santamaría-Bonfil, G., Froese, T., & Gershenson, C. (2014). The Past, Present, 
and Future of Artificial Life. Frontiers in Robotics and AI, 1, 8. https://doi.org/10.3389/frobt.2014.00008

Backman, H. (2008). Bioart: Biotechnology and Art. Canadian Journal of Optometry, 70(2), 
Article 2. https://doi.org/10.15353/cjo.70.702

Jagodzinski, Jan. (2020). Thinking ‘The End of Times’: The Significance of Bioart|BioArt for  
Art|Education. In Jan Jagodzinski (Ed.), Pedagogical Explorations in a Posthuman Age: Essays on Designer Capitalism, Eco-Aestheticism, and Visual and Popular Culture as West-East Meet (pp. 271–291). Springer International Publishing. https://doi.org/10.1007/978-3-030-48618-1_11

Loew, L. M., & Schaff, J. C. (2001). The Virtual Cell: A software environment for 
computational cell biology. Trends in Biotechnology, 19(10), 401–406. https://doi.org/10.1016/S0167-7799(01)01740-1

Simou, P., Tiligadis, K., & Alexiou, A. (2013). Exploring Artificial Intelligence Utilizing BioArt. 
In H. Papadopoulos, A. S. Andreou, L. Iliadis, & I. Maglogiannis (Eds.), Artificial Intelligence Applications and Innovations (pp. 687–692). Springer. https://doi.org/10.1007/978-3-642-41142-7_69






![Book logo](/FreeCells-1.jpg)

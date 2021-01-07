+++
# Research experience widget.
widget = "projects"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Research Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Graduate Research Assistant"
  company = "University of Florida"
  company_url = "https://mae.ufl.edu/dspearot/research.html"
  location = "Gainesville, Florida"
  date_start = "2017-06-01"
  date_end = "2021-08-01"
  description = """
  
  **Advisor**: Dr. Douglas E. Spearot
  **Research Area**: Mesoscale Modeling of Defect-Mediated Plasticity in Metals
  
  Developed and implemented frameworks and tools for the discrete dislocation dynamics (DDD) simulation method to investigate dislocation-mediated plasticity in metals.
  * Developed and implemented virtual x-ray diffraction (XRD) algorithms for generating line profiles from dislocation microstructures obtained using DDD
  
  * Generated virtual XRD line profile databases for aluminum, tantalum, and iron, which have been used to train machine learning models to quantify dislocation densities from experimentally measured XRD profiles
  
  * Implemented atomistically-derived dislocation mobility laws to accurately characterize the role of dislocation core structure on the kinetics of dislocation slip and the evolution of dislocation networks
  
  * Developed and implemented a framework for modeling equilibrium and non-equilibrium grain boundary structures in DDD, which has been used to gain new insights into the influence of intergranular stresses on dislocation slip transmission in aluminum
  
  * Parallelized algorithms for improved efficiency on high performance computing clusters
    """
    
 [[experience]]
  title = "Visiting Scientist"
  company = "Los Alamos National Laboratory"
  location = "Los Alamos, New Mexico"
  date_start = "2018-05-01"
  date_end = "2019-08-01"
  description = """
  
  **Host/Mentor**: Dr. Laurent Capolungo
  
   Collaborated with postdoctoral researchers and staff scientists in the Materials Science in Radiation and Dynamics Extremes group at Los Alamos National Laboratory on the development of algorithms and methods for discrete dislocation dynamics.
   """  
   
  [[experience]]
  title = "Student Researcher"
  company = "University of Florida"
  location = "Gainesville, Florida"
  date_start = "2016-08-01"
  date_end = "2017-05-01"
  description = """
  
  **Mentor**: Dr. Bhavani Sankar
  
   Analyzed the biaxial flexural deformation behavior of hydroxyapatite-polysulfone laminated composites using the finite element method. Simulated and analyzed stress distributions in laminates with different layer thickness ratios to identify the influence of layer thicknesses on the principal tensile and the interlaminar shear stresses, which determine the load bearing capacity of the composite.
   """  

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
    
  # Background color.
  color = "navy"
  
  # Background gradient.
  gradient_start = "LightSkyBlue"
  gradient_end = "White"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false  
  

+++

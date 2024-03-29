﻿##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is MATLAB code to produce IPCC AR6 WGI Figure 2.17, panel a
# Creator: Juan A. Rivera, IANIGLA/CONICET 
# Contact: jrivera@mendoza-conicet.gob.ar
# Last updated on: July 8th, 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: HCextent_NH.m: This code plots the time series of annual mean Northern Hemisphere Hadley Cell extent for the period 1980-2019 for a variety of datasets
			HCextent_SH.m: This code plots the time series of annual mean Southern Hemisphere Hadley Cell extent for the period 1980-2019 for a variety of datasets
# - Input data: MATLAB file of annual mean Northern and Southern Hemisphere Hadley Cell extent from a variety of datasets. The file can be accessed at: *Link to CEDA catalogue*
# - Output variables: The code plots the panels of figure 2.17 panel a as in the report
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: MATLAB R2017b
# - Landing page to access the software: https://www.mathworks.com/products/matlab.html?s_tid=hp_products_matlab 
# - Operating System: Microsoft Windows 10 Home Single Language, last update June 13th, 2021
# - Environment required to compile and run: Not applicable
#  ----------------------------------------------------------------------------------------------------
#
#  License: Apache 2.0
# ----------------------------------------------------------------------------------------------------
# How to cite:
Gulev, S.K., P.W. Thorne, J. Ahn, F.J. Dentener, C.M. Domingues, S. Gerland, D. Gong, D.S. Kaufman, H.C. Nnamchi, J. Quaas, J.A. Rivera, S. Sathyendranath, S.L. Smith, B. Trewin, K. von Schuckmann, and R.S. Vose, 2021: Changing State of the Climate System. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change[Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 287–422, doi:10.1017/9781009157896.004.
# When citing this code, please include both the code citation and the following citation for the related report component:
 https://doi.org/10.5281/zenodo.6340021
########################################################################














Am keeping this for reference:
# ----------------------------------------------------------------------------------------------
# Acknowledgement: The template for this file was created by Lina E. Sitz (https://orcid.org/0000-0002-6333-4986), Paula A. Martinez (https://orcid.org/0000-0002-8990-1985), and J. B. Robin Matthews (https://orcid.org//0000-0002-6016-7596)

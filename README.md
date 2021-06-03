## Table of contents

1. <a href="#1.-STEP-I:-Setting-up-Problem">STEP I: Setting up Problem</a>        
    1.1. <a href="#1.1-Introduction">Introduction</a>    
    1.2. <a href="#1.2-Data-Description">Data Description</a>    
    1.3. <a href="#1.3-Problem-Statement">Problem Statement</a>    
    
2. <a href="#2.-Import-Libraries">Import Libraries</a>
3. <a href="#3.-Read-Data">Read Data</a>
4. <a href="#4.-EDA">EDA</a>        
    4.1. <a href="#4.1-Remove-Duplicate-Records">Remove Duplicate Records</a>    
    4.2. <a href="#4.2-IMDB-Score-and-Movie-Count-Analysis">IMDB Score and Movie Count Analysis</a>    
    4.3. <a href="#4.3-Language-Distribution">Language Distribution</a>    
    4.4. <a href="#4.4-Color-Distribution">Color Distribution</a>    
    4.5. <a href="#4.5-Movie-Year-Vs-Gross">Movie Year Vs Gross</a>    
    4.6. <a href="#4.6-Top-10-IMDB-Rating-Movies">Top 10 IMDB Rating Movies</a>    
    4.7. <a href="#4.7-Indian-Top-5-Rated-Movies">Indian Top 5 Rated Movies</a>        
    4.8. <a href="#4.8-Correlation">Correlation</a>        
    4.9. <a href="#4.9-Top-20-Movies-Country-based-on-IMDB-Rating">Top 20 Movies Country based on IMDB Rating</a>        
    4.10. <a href="#4.10-Top-20-Directors-based-on-the-IMDB-Rating">Top 20 Directors based on the IMDB Rating</a>        
    4.11. <a href="#4.11-Null-Count-and-Dtype-Check">Null Count and Dtype Check</a>      
5. <a href="#5.-Modelling">Modelling</a>       
    5.1. <a href="#5.1-Drop-Column---movie_imdb_link,-color,-language,-director_name,-actor_1_name,-actor_2_name,-actor_3_name,-movie_title,-plot_keywords,-genres">Drop Column - movie_imdb_link, color, language, director_name, actor_1_name, actor_2_name, actor_3_name, movie_title, plot_keywords, genres</a>      
    5.2. <a href="#5.2-Drop-NaN-Rows-based-on-specific-column-list">Drop NaN Rows based on specific column list </a>    
    5.3. <a href="#5.3-Fill-NaN-rows-for-'content_rating'-by-'R'">Fill NaN rows for 'content_rating' by 'R'</a>    
    5.4. <a href="#5.4-Fill-NaN-rows-for-'country'-by-'other'">Fill NaN rows for 'country' by 'other'</a>    
    5.5. <a href="#5.5-Fill-NaN-rows-for-'aspect_ratio',-'budget',-'gross'-by-median">Fill NaN rows for 'aspect_ratio', 'budget', 'gross' by median</a>    
    5.6. <a href="#5.6-Feature-Engineering---Get-Profit-and-Profit-Percentage-Column">Feature Engineering - Get Profit and Profit Percentage Column</a>    
    5.7. <a href="#5.7-Correlation-Based-Feature-Engineering">Correlation Based Feature Engineering</a>    
    5.8. <a href="#5.8-Binning-of-IMDB-Score">Binning of IMDB Score</a>        
    5.9. <a href="#5.9-One-Hot-Encoding-of-Data">One Hot Encoding of Data</a>        
    5.10. <a href="#5.10-Creation-of-Train-and-Test-Set">Creation of Train and Test Set</a>            
    5.11. <a href="#5.11-Standardization-of-columns-Scaling">Standardization of columns Scaling</a>            
    5.12. <a href="#5.12-Logistic-Regression">Logistic-Regression</a>                
    5.13. <a href="#5.13-Random-Forest">Random Forest</a>                
    5.14. <a href="#5.14-XGBOOST">XGBOOST</a>                
    5.15. <a href="#5.15-Model-Comparison">Model Comparison</a>             
6. <a href="#6.-Future Work">Future Work</a>           

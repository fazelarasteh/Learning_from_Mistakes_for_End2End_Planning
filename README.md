# Learning_from_Mistakes_for_End2End_Planning

NOTE: We are actively testing and improving our models with Nuplan data. This page is to report our latest results.

    \centering
    \begin{tabular}{|c||c|c|c|c|c|}
         \hline
         & data-set&overall-score & ego-progress-along-expert-route & no-ego-at-fault-collisions & time-to-collision-within-bound \\
         \hline
         \hline
         
         \makecell{UrbanDrive \\ (with augmentation) \cite{urban_driver}}  & \makecell{private testset \\ (leader board)}&0.6821 & 0.8417 & 0.8952 & 0.8065  \\
         \hline
         \makecell{IDMPlanner \cite{IDM}} & \makecell{private testset \\ (leader board)} & 0.7243 & 0.8144 & 0.8367 & 0.7762  \\
         \hline
         \makecell{CS-Tu \cite{leader_board1}} & \makecell{private testset \\ (leader board)}& 0.9276 & 0.9141 & 0.9879 & 0.9254 \\
         \hline
         \hline
         
         \makecell{SimplePlanner}  & public testset & 0.294318 & 0.496391 & 0.732179 & 0.691446 \\
         \hline
         \makecell{UrbanDrive \\ (without augmentation)}  &public testset & 0.388708  & 0.898438  & 0.639957 & 0.57265   \\
         \hline
         \makecell{IDMPlanner} & public testset & 0.702864 & 0.837308 & 0.865385 &  0.752137 \\
         \hline
         \makecell{IL}  & public testset & - & - & - & - \\
         \hline
         \makecell{LFM \\ ($valid=\{ \text{not collision}\}$)} & public testset & - & - & - & -  \\
         \hline
         \makecell{LFM \\ ($valid=\{ \text{not collision},$ \\$ \text{not stuck}\}$)} & public testset & - & - & - & -  \\
         \hline
    \end{tabular}
    \caption{ \small Nuplan closed-loop metrics}

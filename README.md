Instructions

    Click on the ipynb file
    Edit the 'github.com' in the URL to 'githubtocolab.com', click enter
    Click to Run All at the top left of screen
    This will provide a plot and generate a csv of the data requested
    You can then edit the Tickers, Period (Quarterly or Annually), and Financial Metrics in cell 43

    Note you will need to identiify whether those metrics come from the Income Statement, Balance Sheet, 
    or Cash Flows, since that must be input as part of the tuple in desired_metrics_to_plot list.

    If you update the metrics, tickers or period run cell 44 again if you would like to generate the requested 
    data via csv. The csv can be accessed by clicking the folder icon on the left and downloading the file or 
    double clicking to view the pane on the right

    You can view the full list of metrics by removing the '#'s from lines 15,16,17 in cell 43, which are 
    commented out.

    """
    #print("\nAvailable Metrics (Statement, Metric Name):")
    #for i, (stmt, metric) in enumerate(available_metrics):
    #    print(f"{i+1}. [{stmt[:3].upper()}] {metric}")
    """
    

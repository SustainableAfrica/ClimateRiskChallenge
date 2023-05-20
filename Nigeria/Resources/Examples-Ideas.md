# Sample Ideas, Model Recommendations, & Checklist

## Example use cases (to stimulate thinking about target applications)
 
### National Authorities risk and resilience planning
National Authorities (NAs) can use more accurate estimates of the probabilities of crop production and risks to do better short to long term resilience planning. Reducing costs of impacts, supporting business productivity and regulating market dynamics. Sub examples
- Seasonal risks to and properties of crops. 1-4 month lead times of building up risks of biophysical risks (crop failure, drought, bumper yields), giving enough time to take actions in order to minimise costs and optimise benefits.
- Longer term risks in suitability of areas for crop production, informing longer term land management planning to optimise crop production for the right locations under changing environmental and other conditions.

### Insurance and reinsurance companies
Insurance providers looking to provide improved or entirely new insurance to mitigate impacts of crop failures. Sub examples
- Parametric insurance for farmers - covering them against some of the risk of climate-induced crop losses
- Insurance for other businesses impacted directly or indirectly by agricultural risks such as loss of ingredients, landslides, eutrophication

### Agricultural production and trading
Agribusinesses aiming to meet global demand for Nigeria grown produce looking for ways to better anticipate near to long term impacts of environmental change on production. Examples
- Better anticipating the timing and quality of production in time and space to optimise downstream processing and supply chains
- Securing / retiring production locations over time in light of long term changes in the environment impacting biophysical risks

## Models

### Recommend Teams select from 5 models (CMIP6), 1 out year (2040 - 20 years of data)
3 sets of 5 models
- 2040 Low/High by 5 models
- RCP - Cordex data set better for Nigeria (higher resolution)
- RCP 3.4 (2-2.4 degrees)
- RCP 4.5
- RCP 8.5
- SSP585
- SSP245

### Useful Model Documentation 
- [Worldclim](https://worldclim.org/data/cmip6/cmip6climate.html)

### Relevant Climate Factors
- Humidity
- Temperature (Min, Max, Avg) 
- Precipitation
- Solar radiation
- Wind speed (optional)
- Water vapor (optional)

### Data Granularity
- Ag - monthly downscaled data may be ok

### Other academic papers that may be useful
- To be provided, such as NIMET

## Recommend Teams Define Scope of Analysis
Examples include:
- Crops: Rice and Maize - largely consumed grains
- Analysis on Food Supply/food security in conjunction with population growth
- Investment in ag sector, self sustaining and exporter of grains (to generate revenue) 
- Ag as large source of revenue, to address reduction in oil/gas revenues

## Checklist of things you will probably need to do
1. Agree on target properties and processes for prediction
- Check the objectives and ensure your target properties align with them. You are going to build a capability for informing recommendations to address future agriculture physical risk and resilience issues in Nigeria. What are your target hazards and their properties? What crops? What time frames and spatial scales?
2. Identify resources suitable for predicting target properties
  - Driver and training data
    - Driver data are typically used in predictive models to make predictions but is not directly predicted by the model e.g. you may use hourly temperature data to estimate crop growth but you don’t evaluate the model against its ability to predict temperature.
    - Training data are data about the properties 
    - There is a list of candidate data in the documentation
  - Predictive models
    - Process-based/mechanistic models representing some aspects of how crop/environmental systems function. 
    - There is a list of candidate models in the documentation
    - Purely statistical models that make predictions based on statistically derived relationships between variables in datasets
  - Scenarios
    - What are the most insightful future change scenarios to make predictions over. Different global warming scenarios. 
    - What about socioeconomic and land use policy scenarios for Nigeria? What about different “crisis” scenarios.
  - Model training and evaluation methods
    - There are lots of ways to both calibrate models to improve their accuracy and ways to evaluate the accuracy and suitability of the models. What are the suitable methods?
  - People and skills
    - Do you have the right people and skills on your team to do this?
  - Compute environment
    - Do you have the machines, libraries, storage to do this? Where will the respective data and compute reside? Does it give you the agility to make progress in the best possible way?
    - POINTER TO DOCUMENTATION ON COMPUTE ENVIRONMENT
  - Collaboration environment
    - How is your team going to collaborate on this very technical project? Slack/Teams, Github, Virtual Machines, etc…
3. Decide and implement approach for training and evaluation 
4. Evaluate options on appropriate test data and scenarios
5. Cycle 1-4
6. Generate actionable insights

# DiabetesBuddy

Suggesting actions to avoid high and low blood sugars based on previous trends.

Analysis of insulin pump data:
https://colab.research.google.com/drive/12P2gzYgGEZP7Z7a57jwe3LpVuV3xuVIX?usp=sharing

Columns in CGM datå Medtronic 670G:
Index(['Index', 'Date', 'Time', 'New Device Time', 'BG Source',
       'BG Reading (mg/dL)', 'Linked BG Meter ID', 'Basal Rate (U/h)',
       'Temp Basal Amount', 'Temp Basal Type', 'Temp Basal Duration (h:mm:ss)',
       'Bolus Type', 'Bolus Volume Selected (U)', 'Bolus Volume Delivered (U)',
       'Bolus Duration (h:mm:ss)', 'Prime Type', 'Prime Volume Delivered (U)',
       'Alarm', 'Suspend', 'Rewind', 'BWZ Estimate (U)',
       'BWZ Target High BG (mg/dL)', 'BWZ Target Low BG (mg/dL)',
       'BWZ Carb Ratio (g/U)', 'BWZ Insulin Sensitivity (mg/dL/U)',
       'BWZ Carb Input (grams)', 'BWZ BG Input (mg/dL)',
       'BWZ Correction Estimate (U)', 'BWZ Food Estimate (U)',
       'BWZ Active Insulin (U)', 'BWZ Status', 'Sensor Calibration BG (mg/dL)',
       'Sensor Glucose (mg/dL)', 'ISIG Value', 'Event Marker', 'Bolus Number',
       'Bolus Cancellation Reason', 'BWZ Unabsorbed Insulin Total (U)',
       'Final Bolus Estimate', 'Scroll Step Size', 'Insulin Action Curve Time',
       'Sensor Calibration Rejected Reason', 'Preset Bolus', 'Bolus Source',
       'BLE Network Device', 'Network Device Associated Reason',
       'Network Device Disassociated Reason',
       'Network Device Disconnected Reason', 'Sensor Exception',
       'Preset Temp Basal Name'],
      dtype='object')
      

06/28/2021: Added graph to analys trend of 'Sensor Glucose (mg/dL)' over time, did some modifications to dataframe as shown in the colab book

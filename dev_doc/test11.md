	
	Process API
	
	Progress of the process
	
	GET /api/flights/:flight_id/process/progress
	
	
	Request
	
	Route
	  GET /api/flights/:flight_id/process/progress?token=TOKEN_OF_USER_1
	
	
	Response
	
	Status
	  200 OK
	
	Body
	 {
	   "time": {
	      "std": "2014-04-01T02:00:00.000+09:00",
	      "etd": null,
	      "timeleft": 120,
	      "calculated_at": "2014-04-01T00:00:00+09:00"
	   },
	   ÅgprogressÅh: [
	      {
	        Ågprogress_idÅh: 1,
	        "process_id": 1,
	        "operation_id": 1,
	        "status": NULL,
	        ÅgnameÅh: ÅgDEPLANEÅh,
	        "plan_start": "35",
	        "plan_end": "30",
	        "plan_start_time": NULL,
	        "plan_end_time": NULL,
	        "work_start": "35",
	        "work_end": "25",
	        "work_start_time": "2014-06-11T09:25:00",
	        "work_end_time": "2014-60-11T09:35:20"
	      },
	      {
	        Ågprogress_idÅh: 2,
	        "process_id": 1,
	        "operation_id": 1,
	        "status": NULL,
	        ÅgnameÅh: ÅgBOADINGÅh,
	        "plan_start": "15",
	        "plan_end": "3",
	        "plan_start_time": NULL,
	        "plan_end_time": NULL,
	        "work_start": NULL,
	        "work_end": NULL,
	        "work_start_time": NULL,
	        "work_end_time": NULL
	      },
	      {
	        Ågprogress_idÅh: 3,
	        "process_id": 2,
	        "operation_id": 1,
	        "status": NULL,
	        ÅgnameÅh: NULL,
	        "plan_start": "30",
	        "plan_end": "20",
	        "plan_start_time": NULL,
	        "plan_end_time": NULL,
	        "work_start": "25",
	        "work_end": NULL,
	        "work_start_time": "2014-06-10T09:35:12",
	        "work_end_time": NULL
	      },
	      {
	        Ågprogress_idÅh: 4,
	        "process_id": 6,
	        "operation_id": 1,
	        "status": NULL,
	        ÅgnameÅh: NULL,
	        "plan_start": NULL,
	        "plan_end": NULL,
	        "plan_start_time": NULL,
	        "plan_end_time": NULL,
	        "work_start": NULL,
	        "work_end": NULL,
	        "work_start_time": NULL,
	        "work_end_time": NULL
	      }
	    ]
	  }

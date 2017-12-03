# ng-xslx

Installation

    bower install --save angular-xlsx
    
    npm install --save ng-xlsx

Usage

    var result = svc.writeXlsx([
		{
			sheetName: "testSheet",
			columnDefs: [
				{field: "colA", displayName: "Column A"}
			],
			data: [
				{colA: 1}
			]
		}
		]);

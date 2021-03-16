function showFile(fileName) {
    var url = window.location.href;
    serverUrl = url.split("//")[1].split("/")[0];
     var fileUrl = "http://"+serverUrl +'/SimpleFlagService.goss/' + fileName;

    var url = "/pdf/static/pdfjs/web/viewer.html?file="+fileUrl;
    window.open(url);
}
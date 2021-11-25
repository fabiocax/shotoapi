# shotoapi


from shotoapi import ShotoApi
api=ShotoApi()

api.apikey("apikey")

api.endpoint("https://api.shoto.com.br/")




api.study("teste")

api.search_face("imagens.jpeg")

api.analysis_faces("imagens.jpeg")

api.enconding_faces("tmp.png",name)
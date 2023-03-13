# inmotion-app-translation
A repository for INMOTION APP translation.

## How to contribute
There are translations files for each language that you can edit. You can find the appropriate language by looking at the country identifier in the file name. So if you want to translate to German, you would look for the file de_DE.dart. In order to edit the file, either fork the repository and make the changes, or simply go to the file and click on the pencil icon to edit it directly (top right corner).

Make sure to add your translation between the two empty quotations marks. You can see an example of this by looking at the initial English translations.

After fork, it is highly recommended to create a new branch for translation work. For example, create a 'add fr_FR' branch based on the main branch to start the French translation work for France.

When you're happy with your changes, open a pull request so they can be added. Please open pull requests often, so other people can see what has been done already! Don't forget to include your name / username that you want to have added to the contributors.md file. The people in this file will be added to the list of contributors that will be available in the app!

## Comments
Throughout the translations file, you will see some comments (preceded with //). These are there to give you an indication where the translation is used. That way, if you aren't sure about a translation, you can check if it would fit by going to the right part in the app. These comments should not be translated, as they are only used to give context to the rest of the words.

## Variables
Sometimes you will run into constructs such as %s or %d. These are variables and should be included in your translation! Later on, the app will substitute these constructs by the appropriate words. An example would be this: "%dmin ago" would become "3min ago" in the app.

## Additional info

### Unsure about translation?
If you are unsure about a translation, it is better to leave it blank and open an issue to discuss about it with other people. Just list the word(s) you are uncertain of (and in the require language) and other people might be able to help you out with it!

### Missing your language?
If your language isn't added yet, you can just copy the en_US.dart file, then modify the file name to lang_region.dart, and then translate it. So if you want to translate to German, you would copy the en_US.dart file and then rename to de_DE.dart, then you could begain your translation.

### Better translation for already translated part?
If you come across part of the app that you would translate different: you're free to edit existing translations. This also holds for the original English translations: if you believe you have a better way to word something, go ahead!

## Translation file name and country/region chart

| ISO Code Language |           Country/Region           | ISO Code Language |              Country/Region              | ISO Code Language |           Country/Region           |
|:-----------------:|:----------------------------------:|-------------------|:----------------------------------------:|-------------------|:----------------------------------:|
| af_ZA             | Afrikaans   (South Africa)         | en_NR             | English   (Nauru)                        | fr_RE             | French   (Réunion)                 |
| ar_AE             | Arabic (United Arab Emirates)      | en_NU             | English (Niue)                           | fr_RW             | French (Rwanda)                    |
| ar_AR             | Arabic (Arabic)                    | en_NZ             | English (New Zealand)                    | fr_SC             | French (Seychelles)                |
| ar_BH             | Arabic (Bahrain)                   | en_PG             | English (Papua New Guinea)               | fr_SN             | French (Senegal)                   |
| ar_DJ             | Arabic (Djibouti)                  | en_PH             | English (Philippines)                    | fr_TD             | French (Chad)                      |
| ar_DZ             | Arabic (Algeria)                   | en_PI             | English (Pirate)                         | fr_TG             | French (Togo)                      |
| ar_EG             | Arabic (Egypt)                     | en_PK             | English (Pakistan)                       | fr_VU             | French (Vanuatu)                   |
| ar_EH             | Arabic (Western Sahara)            | en_PN             | English (Pitcairn Islands)               | fr_WF             | French (Wallis and Futuna)         |
| ar_ER             | Arabic (Eritrea)                   | en_PR             | English (Puerto Rico)                    | fr_YT             | French (Mayotte)                   |
| ar_IL             | Arabic (Israel)                    | en_PW             | English (Palau)                          | fy_NL             | Frisian (Netherlands)              |
| ar_IQ             | Arabic (Iraq)                      | en_RW             | English (Rwanda)                         | ga_GB             | Irish (United Kingdom)             |
| ar_JO             | Arabic (Jordan)                    | en_SB             | English (Solomon Islands)                | ga_IE             | Irish (Ireland)                    |
| ar_KM             | Arabic (Comoros)                   | en_SC             | English (Seychelles)                     | gl_ES             | Galician (Spain)                   |
| ar_KW             | Arabic (Kuwait)                    | en_SD             | English (Sudan)                          | he_IL             | Hebrew (Israel)                    |
| ar_LB             | Arabic (Lebanon)                   | en_SG             | English (Singapore)                      | hi_FJ             | Hindi (Fiji)                       |
| ar_LY             | Arabic (Libya)                     | en_SH             | English (Saint Helena)                   | hi_IN             | Hindi (India)                      |
| ar_MA             | Arabic (Morocco)                   | en_SL             | English (Sierra Leone)                   | hi_PK             | Hindi (Pakistan)                   |
| ar_MR             | Arabic (Mauritania)                | en_SO             | English (Somalia)                        | hr_BA             | Croatian (Bosnia and Herzegovina)  |
| ar_OM             | Arabic (Oman)                      | en_SS             | English (South Sudan)                    | hr_HR             | Croatian (Croatia)                 |
| ar_PS             | Arabic (West Bank and Gaza)        | en_SZ             | English (Swaziland)                      | hu_HU             | Hungarian (Hungary)                |
| ar_QA             | Arabic (Qatar)                     | en_TC             | English (Turks and Caicos Islands)       | hy_AM             | Armenian (Armenia)                 |
| ar_SA             | Arabic (Saudi Arabia)              | en_TO             | English (Tonga)                          | id_ID             | Indonesian (Indonesia)             |
| ar_SD             | Arabic (Sudan)                     | en_TT             | English (Trinidad and Tobago)            | is_IS             | Icelandic (Iceland)                |
| ar_SO             | Arabic (Somalia)                   | en_TV             | English (Tuvalu)                         | it_CH             | Italian (Switzerland)              |
| ar_SY             | Arabic (Syria)                     | en_TZ             | English (Tanzania)                       | it_IT             | Italian (Italy)                    |
| ar_TD             | Arabic (Chad)                      | en_UD             | English (Upside Down)                    | it_SM             | Italian (San Marino)               |
| ar_TN             | Arabic (Tunisia)                   | en_UG             | English (Uganda)                         | it_VA             | Italian (Vatican City)             |
| ar_YE             | Arabic (Yemen)                     | en_US             | English (United States)                  | ja_JP             | Japanese (Japan)                   |
| az_AZ             | Azerbaijani (Azerbaijan)           | en_VC             | English (St. Vincent and the Grenadines) | ja_PW             | Japanese (Palau)                   |
| be_BY             | Belarusian (Belarus)               | en_VG             | English (British Virgin Islands)         | ka_GE             | Georgian (Georgia)                 |
| bg_BG             | Bulgarian (Bulgaria)               | en_VI             | English (United States Virgin Islands)   | km_KH             | Khmer (Cambodia)                   |
| bn_IN             | Bengali (India)                    | en_VU             | English (Vanuatu)                        | ko_KP             | Korean (DPRK)                      |
| bs_BA             | Bosnian (Bosnia and Herzegovina)   | en_WS             | English (Samoa)                          | ko_KR             | Korean (South Korea)               |
| ca_AD             | Catalan (Andorra)                  | en_ZA             | English (South Africa)                   | ku_TR             | Kurdish (Turkey)                   |
| ca_ES             | Catalan (Spain)                    | en_ZM             | English (Zambia)                         | la_VA             | Latin (Vatican City)               |
| cs_CZ             | Czech (Czech Republic)             | en_ZW             | English (Zimbabwe)                       | lt_LT             | Lithuanian (Lithuania)             |
| cs_SK             | Czech (Slovak Republic)            | eo_EO             | Esperanto (Esperanto)                    | lv_LV             | Latvian (Latvia)                   |
| cy_GB             | Welsh (United Kingdom)             | es_AR             | Spanish (Argentina)                      | mk_MK             | Macedonian (Macedonia)             |
| da_DK             | Danish (Denmark)                   | es_BO             | Spanish (Bolivia)                        | ml_IN             | Malayalam (India)                  |
| da_FO             | Danish (Faeroe Islands)            | es_CL             | Spanish (Chile)                          | ms_BN             | Malay (Brunei)                     |
| da_GL             | Danish (Greenland)                 | es_CO             | Spanish (Colombia)                       | ms_ID             | Malay (Indonesia)                  |
| de_AT             | German (Austria)                   | es_CR             | Spanish (Costa Rica)                     | ms_MY             | Malay (Malaysia)                   |
| de_BE             | German (Belgium)                   | es_CU             | Spanish (Cuba)                           | ms_SG             | Malay (Singapore)                  |
| de_CH             | German (Switzerland)               | es_DO             | Spanish (Dominican Republic)             | mt_MT             | Maltese (Malta)                    |
| de_DE             | German (Germany)                   | es_EC             | Spanish (Ecuador)                        | nb_NO             | Norwegian Bokmål (Norway)          |
| de_LI             | German (Liechtenstein)             | es_ES             | Spanish (Spain)                          | ne_NP             | Nepali (Nepal)                     |
| de_LU             | German (Luxembourg)                | es_GI             | Spanish (Gibraltar)                      | nl_AN             | Dutch (Netherlands Antilles)       |
| de_NA             | German (Namibia)                   | es_GQ             | Spanish (Equatorial Guinea)              | nl_AW             | Dutch (Aruba)                      |
| el_CY             | Greek (Cyprus)                     | es_GT             | Spanish (Guatemala)                      | nl_BE             | Dutch (Belgium)                    |
| el_GR             | Greek (Greece)                     | es_HN             | Spanish (Honduras)                       | nl_CW             | Dutch (Curaçao)                    |
| en_AG             | English (Antigua and Barbuda)      | es_LA             | Spanish (Spanish)                        | nl_NL             | Dutch (Netherlands)                |
| en_AI             | English (Anguilla)                 | es_MX             | Spanish (Mexico)                         | nl_SR             | Dutch (Suriname)                   |
| en_AS             | English (American Samoa)           | es_NI             | Spanish (Nicaragua)                      | nl_SX             | Dutch (Sint Maarten (Dutch part))  |
| en_AU             | English (Australia)                | es_PA             | Spanish (Panama)                         | nn_NO             | Norwegian Nynorsk (Norway)         |
| en_BB             | English (Barbados)                 | es_PE             | Spanish (Peru)                           | no_NO             | Norwegian (Norway)                 |
| en_BD             | English (Bangladesh)               | es_PR             | Spanish (Puerto Rico)                    | pa_IN             | Punjabi (India)                    |
| en_BM             | English (Bermuda)                  | es_PY             | Spanish (Paraguay)                       | pl_PL             | Polish (Poland)                    |
| en_BS             | English (The Bahamas)              | es_SV             | Spanish (El Salvador)                    | ps_AF             | Pashto (Afghanistan)               |
| en_BW             | English (Botswana)                 | es_US             | Spanish (United States)                  | pt_AO             | Portuguese (Angola)                |
| en_BZ             | English (Belize)                   | es_UY             | Spanish (Uruguay)                        | pt_BR             | Portuguese (Brazil)                |
| en_CA             | English (Canada)                   | es_VE             | Spanish (Venezuela)                      | pt_CV             | Portuguese (Cape Verde)            |
| en_CK             | English (Cook Islands)             | et_EE             | Estonian (Estonia)                       | pt_GQ             | Portuguese (Equatorial Guinea)     |
| en_CM             | English (Cameroon)                 | eu_ES             | Basque (Spain)                           | pt_GW             | Portuguese (Guinea_Bissau)         |
| en_CW             | English (Curaçao)                  | fa_IR             | Persian (Iran)                           | pt_MO             | Portuguese (Macao)                 |
| en_DM             | English (Dominica)                 | fb_LT             | Leet Speak                               | pt_MZ             | Portuguese (Mozambique)            |
| en_ER             | English (Eritrea)                  | fi_FI             | Finnish (Finland)                        | pt_PT             | Portuguese (Portugal)              |
| en_FJ             | English (Fiji)                     | fo_FO             | Faroese (Faeroe Islands)                 | pt_ST             | Portuguese (São Tomé and Principe) |
| en_FK             | English (Falkland Islands)         | fr_BE             | French (Belgium)                         | pt_TL             | Portuguese (Timor_Leste)           |
| en_FM             | English (Micronesia)               | fr_BF             | French (Burkina Faso)                    | ro_MD             | Romanian (Moldova)                 |
| en_GB             | English (United Kingdom)           | fr_BI             | French (Burundi)                         | ro_RO             | Romanian (Romania)                 |
| en_GD             | English (Grenada)                  | fr_BJ             | French (Benin)                           | ru_BY             | Russian (Belarus)                  |
| en_GG             | English (Guernsey)                 | fr_CA             | French (Canada)                          | ru_KG             | Russian (Kyrgyz Republic)          |
| en_GH             | English (Ghana)                    | fr_CD             | French (Dem. Rep. Congo)                 | ru_KZ             | Russian (Kazakhstan)               |
| en_GI             | English (Gibraltar)                | fr_CF             | French (Central African Republic)        | ru_RU             | Russian (Russia)                   |
| en_GM             | English (The Gambia)               | fr_CG             | French (Congo)                           | ru_TJ             | Russian (Tajikistan)               |
| en_GU             | English (Guam)                     | fr_CH             | French (Switzerland)                     | sk_CZ             | Slovak (Czech Republic)            |
| en_GY             | English (Guyana)                   | fr_CI             | French (Côte d’Ivoire)                   | sk_SK             | Slovak (Slovakia)                  |
| en_HK             | English (Hong Kong)                | fr_CM             | French (Cameroon)                        | sl_SI             | Slovenian (Slovenia)               |
| en_IE             | English (Ireland)                  | fr_DJ             | French (Djibouti)                        | sq_AL             | Albanian (Albania)                 |
| en_IM             | English (Isle of Man)              | fr_FR             | French (France)                          | sq_KS             | Albanian (Kosovo)                  |
| en_IN             | English (India)                    | fr_GA             | French (Gabon)                           | sr_BA             | Serbian (Bosnia and Herzegovina)   |
| en_JE             | English (Jersey)                   | fr_GD             | French (Grenada)                         | sr_ME             | Serbian (Montenegro)               |
| en_JM             | English (Jamaica)                  | fr_GF             | French (French Guianna)                  | sr_RS             | Serbian (Serbia)                   |
| en_KE             | English (Kenya)                    | fr_GN             | French (Guinea)                          | sv_FI             | Swedish (Finland)                  |
| en_KI             | English (Kiribati)                 | fr_GP             | French (Guadeloupe)                      | sv_SE             | Swedish (Sweden)                   |
| en_KN             | English (St. Kitts and Nevis)      | fr_GQ             | French (Equatorial Guinea)               | sw_KE             | Swahili (Kenya)                    |
| en_KY             | English (Cayman Islands)           | fr_HT             | French (Haiti)                           | ta_IN             | Tamil (India)                      |
| en_LC             | English (St. Lucia)                | fr_KM             | French (Comoros)                         | te_IN             | Telugu (India)                     |
| en_LK             | English (Sri Lanka)                | fr_LC             | French (St. Lucia)                       | th_TH             | Thai (Thailand)                    |
| en_LR             | English (Liberia)                  | fr_LU             | French (Luxembourg)                      | tl_PH             | Filipino (Philippines)             |
| en_LS             | English (Lesotho)                  | fr_MC             | French (Monaco)                          | tr_CY             | Turkish (Cyprus)                   |
| en_MH             | English (Marshall Islands)         | fr_MF             | French (St. Martin (French part))        | tr_TR             | Turkish (Turkey)                   |
| en_MP             | English (Northern Mariana Islands) | fr_MG             | French (Madagascar)                      | uk_UA             | Ukrainian (Ukraine)                |
| en_MS             | English (Montserrat)               | fr_ML             | French (Mali)                            | vi_VN             | Vietnamese (Vietnam)               |
| en_MT             | English (Malta)                    | fr_MQ             | French (Martinique)                      | zh_CN             | Chinese (China)                    |
| en_MU             | English (Mauritius)                | fr_MU             | French (Mauritius)                       | zh_HK             | Chinese (Hong Kong)                |
| en_MW             | English (Malawi)                   | fr_NC             | French (New Caledonia)                   | zh_MO             | Chinese (Macao)                    |
| en_MY             | English (Malaysia)                 | fr_NE             | French (Niger)                           | zh_SG             | Chinese (Singapore)                |
| en_NA             | English (Namibia)                  | fr_PF             | French (French Polynesia)                | zh_TW             | Chinese (Taiwan)                   |
| en_NG             | English (Nigeria)                  | fr_PM             | French (Saint Pierre and Miquelon)       | 　                | 　                                 |

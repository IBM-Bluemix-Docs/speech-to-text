---

copyright:
  years: 2015, 2021
lastupdated: "2021-06-09"

subcollection: speech-to-text

---

{:support: data-reuse='support'}
{:help: data-hd-content-type='help'}
{:shortdesc: .shortdesc}
{:external: target="_blank" .external}
{:tip: .tip}
{:important: .important}
{:note: .note}
{:deprecated: .deprecated}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}

# About
{: #about}

The {{site.data.keyword.speechtotextfull}} service provides speech transcription capabilities for your applications. The service leverages machine learning to combine knowledge of grammar, language structure, and the composition of audio and voice signals to accurately transcribe the human voice. It continuously updates and refines its transcription as it receives more speech.
{: shortdesc}

The service provides APIs that make it suitable for any application where speech is the input and a textual transcript is the output. It can be used for applications such as voice-automated chatbots, analytic tools for customer-service call centers, and multimedia transcription. Voice control of embedded devices, transcribing meetings and conference calls, and dictating messages and notes are also possible applications, among many others.

The service is ideal for clients who need to extract high-quality speech transcripts from call center audio. Clients in industries such as financial services, healthcare, insurance, and telecommunication can develop cloud-native applications for customer care, customer voice, agent assistance, and other solutions.

This documentation describes managed instances of {{site.data.keyword.speechtotextfull}} that are offered in {{site.data.keyword.cloud_notm}} or in {{site.data.keyword.icp4dfull_notm}} as a Service. If you are interested in on-premises or installed deployments of the service, see [About {{site.data.keyword.speechtotextshort}} for {{site.data.keyword.icp4dfull_notm}}](https://{DomainName}/docs/speech-to-text-data?topic=speech-to-text-data-about#about){: external}.
{: note}

## Speech recognition
{: #about-interfaces}
{: help}
{: support}

The {{site.data.keyword.speechtotextshort}} service offers three interfaces for speech recognition: a WebSocket interface, a synchronous HTTP interface, and an asynchronous HTTP interface. The interfaces let you specify the language of your audio and its format and sampling rate. They also provide many parameters that you can use to tailor how you request audio and the information that the service sends in response. You can also request metrics about the service's analysis of your audio and the audio itself.

-   For more information about the speech recognition interfaces, see [Recognizing speech with the service](/docs/speech-to-text?topic=speech-to-text-service-features#features-recognition) in the service features.
-   For more information about the speech recognition parameters, see [Using speech recognition parameters](/docs/speech-to-text?topic=speech-to-text-service-features#features-parameters) in the service features.

## Customization
{: #about-customization}

The service provides a customization interface that you can use to tune speech recognition for your language and acoustic requirements. You can expand the vocabulary of a model with domain-specific terminology or adapt a model for the acoustic characteristics of your audio. You can also add grammars to restrict the phrases that the service can recognize. For more information, see [Customizing the service](/docs/speech-to-text?topic=speech-to-text-service-features#features-customization) in the service features.

## Language support
{: #about-languages}
{: help}
{: support}

The service supports many languages and dialects:

-   Arabic (Modern Standard)
-   Chinese (Mandarin)
-   Dutch (Belgian and Netherlands)
-   English (Australian, United Kingdom, and United States)
-   French (Canadian and France)
-   German
-   Italian
-   Japanese
-   Korean
-   Portuguese (Brazilian)
-   Spanish (Argentinian, Castilian, Chilean, Colombian, Mexican, and Peruvian)

For more information about the supported languages and about using previous- and next-generation models for speech recognition, see [Using languages and models](/docs/speech-to-text?topic=speech-to-text-service-features#features-languages).

## Audio support
{: #about-formats}

The service accepts audio for transcription in many popular formats:

-   Ogg or Web Media (WebM) audio with the Opus or Vorbis codec
-   MP3 (or MPEG)
-   Waveform Audio File Format (WAV)
-   Free Lossless Audio Codec (FLAC)
-   Linear 16-bit Pulse-Code Modulation (PCM)
-   G.729
-   A-Law
-   Mu-law (or u-law)
-   Basic audio

For more information about the supported audio formats and their characteristics, see [Using audio formats](/docs/speech-to-text?topic=speech-to-text-service-features#features-audio).

## Integrated use cases
{: #about-use-cases}

You can use the {{site.data.keyword.speechtotextshort}} service with other {{site.data.keyword.watson}} services to create applications with even greater scope and functionality:

-   *AI assistant on the phone* - Eliminate hold times and improve customer satisfaction with {{site.data.keyword.conversationfull}} phone integration. Provide live support to your customers with the pre-built integration of {{site.data.keyword.conversationshort}}, {{site.data.keyword.speechtotextshort}}, and {{site.data.keyword.texttospeechfull}}.
-   *Analyze customer calls* - Uncover patterns and conduct root-cause analysis on transcriptions of phone calls between your customers and call center agents. Transcribe audio by using {{site.data.keyword.speechtotextshort}}, and then analyze the transcription with {{site.data.keyword.nlufull}}.
-   *Support agents* - Provide real-time information to improve agent efficiency and focus. Use {{site.data.keyword.speechtotextshort}} to transcribe calls live, and then use {{site.data.keyword.discoveryfull}} to automatically surface relevant information so that your agent can focus on the customer rather than on the search.

## Pricing
{: #about-pricing}

The service offers multiple pricing plans to suit your usage and application needs:

-   For general information about the pricing plans and answers to common questions, see the [Pricing FAQs](/docs/speech-to-text?topic=speech-to-text-faq-pricing).
-   For more information about the pricing plans or to purchase a plan, see the {{site.data.keyword.speechtotextshort}} service in the [{{site.data.keyword.cloud}} Catalog](https://{DomainName}/catalog/speech-to-text){: external}.

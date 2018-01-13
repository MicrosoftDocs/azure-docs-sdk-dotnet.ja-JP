<Type Name="MobileServiceInvalidOperationException" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException">
  <TypeSignature Language="C#" Value="public class MobileServiceInvalidOperationException : InvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceInvalidOperationException extends System.InvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceInvalidOperationException&#xA;Inherits InvalidOperationException" />
  <TypeSignature Language="F#" Value="type MobileServiceInvalidOperationException = class&#xA;    inherit InvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.InvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            モバイル サービスに固有の無効な操作の詳細を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceInvalidOperationException (string message, System.Net.Http.HttpRequestMessage request, System.Net.Http.HttpResponseMessage response);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Net.Http.HttpRequestMessage request, class System.Net.Http.HttpResponseMessage response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.#ctor(System.String,System.Net.Http.HttpRequestMessage,System.Net.Http.HttpResponseMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, request As HttpRequestMessage, response As HttpResponseMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException : string * System.Net.Http.HttpRequestMessage * System.Net.Http.HttpResponseMessage -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException (message, request, response)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="response" Type="System.Net.Http.HttpResponseMessage" />
      </Parameters>
      <Docs>
        <param name="message">
            例外メッセージ。
            </param>
        <param name="request">
            発信するサービス要求します。
            </param>
        <param name="response">
            返されたサービス応答です。
            </param>
        <summary>
            MobileServiceInvalidOperationException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceInvalidOperationException (string message, Exception innerException, System.Net.Http.HttpRequestMessage request, System.Net.Http.HttpResponseMessage response);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException, class System.Net.Http.HttpRequestMessage request, class System.Net.Http.HttpResponseMessage response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.#ctor(System.String,System.Exception,System.Net.Http.HttpRequestMessage,System.Net.Http.HttpResponseMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception, request As HttpRequestMessage, response As HttpResponseMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException : string * Exception * System.Net.Http.HttpRequestMessage * System.Net.Http.HttpResponseMessage -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException (message, innerException, request, response)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="response" Type="System.Net.Http.HttpResponseMessage" />
      </Parameters>
      <Docs>
        <param name="message">
            例外メッセージ。
            </param>
        <param name="innerException">
            この例外の内部例外
            </param>
        <param name="request">
            発信するサービス要求します。
            </param>
        <param name="response">
            返されたサービス応答です。
            </param>
        <summary>
            MobileServiceInvalidOperationException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceInvalidOperationException (string message, System.Net.Http.HttpRequestMessage request, System.Net.Http.HttpResponseMessage response, Newtonsoft.Json.Linq.JObject value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Net.Http.HttpRequestMessage request, class System.Net.Http.HttpResponseMessage response, class Newtonsoft.Json.Linq.JObject value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.#ctor(System.String,System.Net.Http.HttpRequestMessage,System.Net.Http.HttpResponseMessage,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, request As HttpRequestMessage, response As HttpResponseMessage, value As JObject)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException : string * System.Net.Http.HttpRequestMessage * System.Net.Http.HttpResponseMessage * Newtonsoft.Json.Linq.JObject -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException (message, request, response, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="response" Type="System.Net.Http.HttpResponseMessage" />
        <Parameter Name="value" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="message">
            例外メッセージ。
            </param>
        <param name="request">
            発信するサービス要求します。
            </param>
        <param name="response">
            返されたサービス応答です。
            </param>
        <param name="value">
            サーバーの応答が JObject として逆シリアル化します。
            </param>
        <summary>
            MobileServiceInvalidOperationException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public System.Net.Http.HttpRequestMessage Request { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.Http.HttpRequestMessage Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.Request" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Request As HttpRequestMessage" />
      <MemberSignature Language="F#" Value="member this.Request : System.Net.Http.HttpRequestMessage" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpRequestMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            発信するサービス要求を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public System.Net.Http.HttpResponseMessage Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.Http.HttpResponseMessage Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="member this.Response : System.Net.Http.HttpResponseMessage" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            返されたサービス応答を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.Linq.JObject Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.Linq.JObject Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As JObject" />
      <MemberSignature Language="F#" Value="member this.Value : Newtonsoft.Json.Linq.JObject" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Linq.JObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サーバーの応答が JObject として逆シリアル化します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
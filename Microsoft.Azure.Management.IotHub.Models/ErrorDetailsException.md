<Type Name="ErrorDetailsException" FullName="Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
  <TypeSignature Language="C#" Value="public class ErrorDetailsException : Microsoft.Rest.RestException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorDetailsException extends Microsoft.Rest.RestException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorDetailsException&#xA;Inherits RestException" />
  <TypeSignature Language="F#" Value="type ErrorDetailsException = class&#xA;    inherit RestException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.RestException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ErrorDetails 情報で無効な応答にスローされる例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetailsException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ErrorDetailsException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetailsException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException : string -&gt; Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException" Usage="new Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外メッセージ。</param>
        <summary>
            ErrorDetailsException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetailsException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException : string * Exception -&gt; Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException" Usage="new Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外メッセージ。</param>
        <param name="innerException">内部例外。</param>
        <summary>
            ErrorDetailsException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.ErrorDetails Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.ErrorDetails Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As ErrorDetails" />
      <MemberSignature Language="F#" Value="member this.Body : Microsoft.Azure.Management.IotHub.Models.ErrorDetails with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.ErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または body オブジェクトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpRequestMessageWrapper Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpRequestMessageWrapper Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpRequestMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Rest.HttpRequestMessageWrapper with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpRequestMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            関連付けられている HTTP 要求に関する情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpResponseMessageWrapper Response { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpResponseMessageWrapper Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpResponseMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Rest.HttpResponseMessageWrapper with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpResponseMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            関連付けられている HTTP 応答に関する情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ErrorResponseException" FullName="Microsoft.Azure.OperationalInsights.Models.ErrorResponseException">
  <TypeSignature Language="C#" Value="public class ErrorResponseException : Microsoft.Rest.RestException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorResponseException extends Microsoft.Rest.RestException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorResponseException&#xA;Inherits RestException" />
  <TypeSignature Language="F#" Value="type ErrorResponseException = class&#xA;    inherit RestException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.RestException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ErrorResponse 情報で無効な応答にスローされる例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponseException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ErrorResponseException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponseException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.Models.ErrorResponseException : string -&gt; Microsoft.Azure.OperationalInsights.Models.ErrorResponseException" Usage="new Microsoft.Azure.OperationalInsights.Models.ErrorResponseException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外メッセージ。</param>
        <summary>
            ErrorResponseException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponseException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.Models.ErrorResponseException : string * Exception -&gt; Microsoft.Azure.OperationalInsights.Models.ErrorResponseException" Usage="new Microsoft.Azure.OperationalInsights.Models.ErrorResponseException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外メッセージ。</param>
        <param name="innerException">内部例外。</param>
        <summary>
            ErrorResponseException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.OperationalInsights.Models.ErrorResponse Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.OperationalInsights.Models.ErrorResponse Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As ErrorResponse" />
      <MemberSignature Language="F#" Value="member this.Body : Microsoft.Azure.OperationalInsights.Models.ErrorResponse with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationalInsights.Models.ErrorResponse</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpRequestMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Rest.HttpRequestMessageWrapper with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpResponseMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Rest.HttpResponseMessageWrapper with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="errorResponseException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
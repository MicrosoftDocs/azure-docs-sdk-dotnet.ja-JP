<Type Name="ErrorResponse" FullName="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse">
  <TypeSignature Language="C#" Value="public class ErrorResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorResponse" />
  <TypeSignature Language="F#" Value="type ErrorResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            エラー応答では、ARM が着信要求を処理できないことを示します。 その理由は、エラー メッセージで提供されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ErrorResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse (string httpStatus = null, string errorCode = null, string errorMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string httpStatus, string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional httpStatus As String = null, Optional errorCode As String = null, Optional errorMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse : string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse (httpStatus, errorCode, errorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpStatus" Type="System.String" />
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="httpStatus">Http ステータス コード。</param>
        <param name="errorCode">エラー コード。</param>
        <param name="errorMessage">操作が失敗した理由を示すエラー メッセージです。</param>
        <summary>
            ErrorResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラー コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作が失敗した理由を示すエラー メッセージを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatus">
      <MemberSignature Language="C#" Value="public string HttpStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.HttpStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatus As String" />
      <MemberSignature Language="F#" Value="member this.HttpStatus : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.HttpStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または http ステータス コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
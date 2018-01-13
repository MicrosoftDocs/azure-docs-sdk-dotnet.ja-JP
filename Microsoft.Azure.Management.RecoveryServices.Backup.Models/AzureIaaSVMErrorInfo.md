<Type Name="AzureIaaSVMErrorInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMErrorInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMErrorInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMErrorInfo" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMErrorInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure IaaS VM のワークロードに固有のエラー情報。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMErrorInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureIaaSVMErrorInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMErrorInfo (Nullable&lt;int&gt; errorCode = null, string errorTitle = null, string errorString = null, System.Collections.Generic.IList&lt;string&gt; recommendations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; errorCode, string errorTitle, string errorString, class System.Collections.Generic.IList`1&lt;string&gt; recommendations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.#ctor(System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional errorCode As Nullable(Of Integer) = null, Optional errorTitle As String = null, Optional errorString As String = null, Optional recommendations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo : Nullable&lt;int&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo (errorCode, errorTitle, errorString, recommendations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorTitle" Type="System.String" />
        <Parameter Name="errorString" Type="System.String" />
        <Parameter Name="recommendations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="errorCode">エラー コード。</param>
        <param name="errorTitle">タイトル: エンティティに関連するエラーのでは通常、します。</param>
        <param name="errorString">ローカライズされたエラーの文字列です。</param>
        <param name="recommendations">エラー コードの上のローカライズされた推奨事項の一覧です。</param>
        <summary>
            AzureIaaSVMErrorInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラー コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorString">
      <MemberSignature Language="C#" Value="public string ErrorString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.ErrorString" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorString As String" />
      <MemberSignature Language="F#" Value="member this.ErrorString : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.ErrorString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはローカライズされたエラー文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorTitle">
      <MemberSignature Language="C#" Value="public string ErrorTitle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorTitle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.ErrorTitle" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorTitle As String" />
      <MemberSignature Language="F#" Value="member this.ErrorTitle : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.ErrorTitle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorTitle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタイトルを設定します。 エンティティに関連するエラーのでは通常、します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Recommendations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Recommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.Recommendations" />
      <MemberSignature Language="VB.NET" Value="Public Property Recommendations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Recommendations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo.Recommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラー コードの上のローカライズされた推奨事項の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
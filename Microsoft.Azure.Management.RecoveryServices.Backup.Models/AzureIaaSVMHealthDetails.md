<Type Name="AzureIaaSVMHealthDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMHealthDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMHealthDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMHealthDetails" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMHealthDetails = class" />
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
            Azure IaaS VM ワークロードに固有の正常性の詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMHealthDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureIaaSVMHealthDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMHealthDetails (Nullable&lt;int&gt; code = null, string title = null, string message = null, System.Collections.Generic.IList&lt;string&gt; recommendations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; code, string title, string message, class System.Collections.Generic.IList`1&lt;string&gt; recommendations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.#ctor(System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As Nullable(Of Integer) = null, Optional title As String = null, Optional message As String = null, Optional recommendations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails : Nullable&lt;int&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails (code, title, message, recommendations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="title" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="recommendations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="code">状態コード</param>
        <param name="title">正常性のタイトル</param>
        <param name="message">正常性メッセージ</param>
        <param name="recommendations">推奨される操作の正常性</param>
        <summary>
            AzureIaaSVMHealthDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Code : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の状態コード
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の正常性メッセージ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Recommendations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Recommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Recommendations" />
      <MemberSignature Language="VB.NET" Value="Public Property Recommendations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Recommendations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Recommendations" />
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
            取得または推奨される操作の正常性の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="title")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のタイトルのヘルス
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
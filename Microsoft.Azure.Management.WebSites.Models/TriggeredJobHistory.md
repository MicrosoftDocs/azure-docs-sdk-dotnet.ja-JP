<Type Name="TriggeredJobHistory" FullName="Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory">
  <TypeSignature Language="C#" Value="public class TriggeredJobHistory : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggeredJobHistory extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggeredJobHistory&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type TriggeredJobHistory = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Web ジョブの履歴をトリガーします。 Web ジョブ実行の情報のトリガーの要素の一覧です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggeredJobHistory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TriggeredJobHistory クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggeredJobHistory (string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt; triggeredJobRuns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt; triggeredJobRuns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional triggeredJobRuns As IList(Of TriggeredJobRun) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory : string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory" Usage="new Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory (id, name, kind, type, triggeredJobRuns)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="triggeredJobRuns" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="triggeredJobRuns">トリガーされた web ジョブの一覧を実行します。</param>
        <summary>
            TriggeredJobHistory クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggeredJobRuns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt; TriggeredJobRuns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt; TriggeredJobRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory.TriggeredJobRuns" />
      <MemberSignature Language="VB.NET" Value="Public Property TriggeredJobRuns As IList(Of TriggeredJobRun)" />
      <MemberSignature Language="F#" Value="member this.TriggeredJobRuns : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobHistory.TriggeredJobRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.triggeredJobRuns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトリガーされた web ジョブの実行の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
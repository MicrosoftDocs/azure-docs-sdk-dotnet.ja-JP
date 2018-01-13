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
            <span data-ttu-id="9919c-101">Web ジョブの履歴をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="9919c-101">Triggered Web Job History.</span></span> <span data-ttu-id="9919c-102">Web ジョブ実行の情報のトリガーの要素の一覧です。</span><span class="sxs-lookup"><span data-stu-id="9919c-102">List of Triggered Web Job Run Information elements.</span></span>
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
            <span data-ttu-id="9919c-103">TriggeredJobHistory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9919c-103">Initializes a new instance of the TriggeredJobHistory class.</span></span>
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
        <param name="id"><span data-ttu-id="9919c-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="9919c-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="9919c-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="9919c-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="9919c-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="9919c-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="9919c-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="9919c-107">Resource type.</span></span></param>
        <param name="triggeredJobRuns"><span data-ttu-id="9919c-108">トリガーされた web ジョブの一覧を実行します。</span><span class="sxs-lookup"><span data-stu-id="9919c-108">List of triggered web job runs.</span></span></param>
        <summary>
            <span data-ttu-id="9919c-109">TriggeredJobHistory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9919c-109">Initializes a new instance of the TriggeredJobHistory class.</span></span>
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
            <span data-ttu-id="9919c-110">取得またはトリガーされた web ジョブの実行の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="9919c-110">Gets or sets list of triggered web job runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
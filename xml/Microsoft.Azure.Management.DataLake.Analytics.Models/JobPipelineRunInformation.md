<Type Name="JobPipelineRunInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation">
  <TypeSignature Language="C#" Value="public class JobPipelineRunInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPipelineRunInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPipelineRunInformation" />
  <TypeSignature Language="F#" Value="type JobPipelineRunInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6e9e4-101">特定のジョブのパイプラインの情報を実行します。</span><span class="sxs-lookup"><span data-stu-id="6e9e4-101">Run info for a specific job pipeline.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPipelineRunInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e9e4-102">JobPipelineRunInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e9e4-102">Initializes a new instance of the JobPipelineRunInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPipelineRunInformation (Nullable&lt;Guid&gt; runId = null, Nullable&lt;DateTimeOffset&gt; lastSubmitTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; runId, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; lastSubmitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation.#ctor(System.Nullable{System.Guid},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional runId As Nullable(Of Guid) = null, Optional lastSubmitTime As Nullable(Of DateTimeOffset) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation : Nullable&lt;Guid&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation (runId, lastSubmitTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="runId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="lastSubmitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="runId"><span data-ttu-id="6e9e4-103">パイプラインの実行 (GUID) のインスタンスの実行の識別子です。</span><span class="sxs-lookup"><span data-stu-id="6e9e4-103">the run identifier of an instance of pipeline executions (a GUID).</span></span></param>
        <param name="lastSubmitTime"><span data-ttu-id="6e9e4-104">このインスタンスが最後に送信された時刻。</span><span class="sxs-lookup"><span data-stu-id="6e9e4-104">the time this instance was last submitted.</span></span></param>
        <summary>
            <span data-ttu-id="6e9e4-105">JobPipelineRunInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e9e4-105">Initializes a new instance of the JobPipelineRunInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSubmitTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastSubmitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastSubmitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation.LastSubmitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSubmitTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastSubmitTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation.LastSubmitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastSubmitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e9e4-106">このインスタンスが最後に送信された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e9e4-106">Gets the time this instance was last submitted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RunId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation.RunId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RunId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation.RunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e9e4-107">パイプラインの実行 (GUID) のインスタンスの実行の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e9e4-107">Gets the run identifier of an instance of pipeline executions (a GUID).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
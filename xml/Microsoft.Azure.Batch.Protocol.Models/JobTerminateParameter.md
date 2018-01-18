<Type Name="JobTerminateParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter">
  <TypeSignature Language="C#" Value="public class JobTerminateParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobTerminateParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobTerminateParameter" />
  <TypeSignature Language="F#" Value="type JobTerminateParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04880-101">ジョブの終了時にオプションです。</span><span class="sxs-lookup"><span data-stu-id="04880-101">Options when terminating a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobTerminateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04880-102">JobTerminateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="04880-102">Initializes a new instance of the JobTerminateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobTerminateParameter (string terminateReason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string terminateReason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional terminateReason As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter : string -&gt; Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter terminateReason" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="terminateReason" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="terminateReason"><span data-ttu-id="04880-103">ジョブの TerminateReason として表示するテキストです。</span><span class="sxs-lookup"><span data-stu-id="04880-103">The text you want to appear as the job's TerminateReason.</span></span> <span data-ttu-id="04880-104">既定値は、'UserTerminate' です。</span><span class="sxs-lookup"><span data-stu-id="04880-104">The default is 'UserTerminate'.</span></span></param>
        <summary>
            <span data-ttu-id="04880-105">JobTerminateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="04880-105">Initializes a new instance of the JobTerminateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateReason">
      <MemberSignature Language="C#" Value="public string TerminateReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TerminateReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter.TerminateReason" />
      <MemberSignature Language="VB.NET" Value="Public Property TerminateReason As String" />
      <MemberSignature Language="F#" Value="member this.TerminateReason : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobTerminateParameter.TerminateReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="terminateReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04880-106">取得またはジョブの TerminateReason として表示するテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="04880-106">Gets or sets the text you want to appear as the job's TerminateReason.</span></span> <span data-ttu-id="04880-107">既定値は、'UserTerminate' です。</span><span class="sxs-lookup"><span data-stu-id="04880-107">The default is 'UserTerminate'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
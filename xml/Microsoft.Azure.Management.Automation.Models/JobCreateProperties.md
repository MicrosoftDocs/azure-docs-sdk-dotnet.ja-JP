<Type Name="JobCreateProperties" FullName="Microsoft.Azure.Management.Automation.Models.JobCreateProperties">
  <TypeSignature Language="C#" Value="public class JobCreateProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobCreateProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.JobCreateProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobCreateProperties" />
  <TypeSignature Language="F#" Value="type JobCreateProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c6827-101">ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c6827-101">The parameters supplied to the create job operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobCreateProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobCreateProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6827-102">JobCreateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6827-102">Initializes a new instance of the JobCreateProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobCreateProperties (Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty runbook);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty runbook) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobCreateProperties.#ctor(Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (runbook As RunbookAssociationProperty)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.JobCreateProperties : Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty -&gt; Microsoft.Azure.Management.Automation.Models.JobCreateProperties" Usage="new Microsoft.Azure.Management.Automation.Models.JobCreateProperties runbook" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="runbook" Type="Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty" />
      </Parameters>
      <Docs>
        <param name="runbook">To be added.</param>
        <summary>
            <span data-ttu-id="c6827-103">必須の引数で JobCreateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6827-103">Initializes a new instance of the JobCreateProperties class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobCreateProperties.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobCreateProperties.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6827-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c6827-104">Optional.</span></span> <span data-ttu-id="c6827-105">取得または、ジョブのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="c6827-105">Gets or sets the parameters of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbook">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobCreateProperties.Runbook" />
      <MemberSignature Language="VB.NET" Value="Public Property Runbook As RunbookAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Runbook : Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobCreateProperties.Runbook" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6827-106">必須。</span><span class="sxs-lookup"><span data-stu-id="c6827-106">Required.</span></span> <span data-ttu-id="c6827-107">取得または runbook を設定します。</span><span class="sxs-lookup"><span data-stu-id="c6827-107">Gets or sets the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunOn">
      <MemberSignature Language="C#" Value="public string RunOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobCreateProperties.RunOn" />
      <MemberSignature Language="VB.NET" Value="Public Property RunOn As String" />
      <MemberSignature Language="F#" Value="member this.RunOn : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobCreateProperties.RunOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6827-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c6827-108">Optional.</span></span> <span data-ttu-id="c6827-109">取得または、ジョブが実行される、グループ名を指定する runOn を設定します。</span><span class="sxs-lookup"><span data-stu-id="c6827-109">Gets or sets the runOn which specifies the group name where the job is to be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="TestJobCreateParameters" FullName="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters">
  <TypeSignature Language="C#" Value="public class TestJobCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TestJobCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TestJobCreateParameters" />
  <TypeSignature Language="F#" Value="type TestJobCreateParameters = class" />
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
            <span data-ttu-id="08035-101">作成のテスト ジョブの操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="08035-101">The parameters supplied to the create test job operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TestJobCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08035-102">TestJobCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08035-102">Initializes a new instance of the TestJobCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TestJobCreateParameters (string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (runbookName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters : string -&gt; Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" Usage="new Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters runbookName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="runbookName">To be added.</param>
        <summary>
            <span data-ttu-id="08035-103">必須の引数で TestJobCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08035-103">Initializes a new instance of the TestJobCreateParameters class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.Parameters" />
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
            <span data-ttu-id="08035-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="08035-104">Optional.</span></span> <span data-ttu-id="08035-105">取得またはテスト ジョブのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="08035-105">Gets or sets the parameters of the test job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunbookName">
      <MemberSignature Language="C#" Value="public string RunbookName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunbookName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.RunbookName" />
      <MemberSignature Language="VB.NET" Value="Public Property RunbookName As String" />
      <MemberSignature Language="F#" Value="member this.RunbookName : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.RunbookName" />
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
            <span data-ttu-id="08035-106">必須。</span><span class="sxs-lookup"><span data-stu-id="08035-106">Required.</span></span> <span data-ttu-id="08035-107">取得または runbook 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="08035-107">Gets or sets the runbook name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunOn">
      <MemberSignature Language="C#" Value="public string RunOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.RunOn" />
      <MemberSignature Language="VB.NET" Value="Public Property RunOn As String" />
      <MemberSignature Language="F#" Value="member this.RunOn : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters.RunOn" />
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
            <span data-ttu-id="08035-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="08035-108">Optional.</span></span> <span data-ttu-id="08035-109">取得または、ジョブが実行される、グループ名を指定する runOn を設定します。</span><span class="sxs-lookup"><span data-stu-id="08035-109">Gets or sets the runOn which specifies the group name where the job is to be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
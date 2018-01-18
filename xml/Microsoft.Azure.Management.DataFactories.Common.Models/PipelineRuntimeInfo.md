<Type Name="PipelineRuntimeInfo" FullName="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo">
  <TypeSignature Language="C#" Value="public class PipelineRuntimeInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineRuntimeInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineRuntimeInfo" />
  <TypeSignature Language="F#" Value="type PipelineRuntimeInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9254e-101">パイプラインのランタイム情報。</span><span class="sxs-lookup"><span data-stu-id="9254e-101">Pipeline runtime information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRuntimeInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9254e-102">PipelineRuntimeInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9254e-102">Initializes a new instance of the PipelineRuntimeInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRuntimeInfo (DateTime deploymentTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime deploymentTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo.#ctor(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deploymentTime As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo : DateTime -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo" Usage="new Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo deploymentTime" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deploymentTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="deploymentTime">To be added.</param>
        <summary>
            <span data-ttu-id="9254e-103">必須の引数で PipelineRuntimeInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9254e-103">Initializes a new instance of the PipelineRuntimeInfo class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentTime">
      <MemberSignature Language="C#" Value="public DateTime DeploymentTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime DeploymentTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo.DeploymentTime" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.DeploymentTime : DateTime with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo.DeploymentTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9254e-104">必須。</span><span class="sxs-lookup"><span data-stu-id="9254e-104">Required.</span></span> <span data-ttu-id="9254e-105">パイプラインの展開時です。</span><span class="sxs-lookup"><span data-stu-id="9254e-105">The deployment time of the pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineState">
      <MemberSignature Language="C#" Value="public string PipelineState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo.PipelineState" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineState As String" />
      <MemberSignature Language="F#" Value="member this.PipelineState : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo.PipelineState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9254e-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9254e-106">Optional.</span></span> <span data-ttu-id="9254e-107">パイプラインの現在の状態を示します。</span><span class="sxs-lookup"><span data-stu-id="9254e-107">Indicates the current state of the pipeline.</span></span> <span data-ttu-id="9254e-108">いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.PipelineState" />です。</span><span class="sxs-lookup"><span data-stu-id="9254e-108">Must be one of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.PipelineState" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
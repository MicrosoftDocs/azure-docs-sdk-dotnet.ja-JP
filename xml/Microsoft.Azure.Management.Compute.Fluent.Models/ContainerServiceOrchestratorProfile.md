<Type Name="ContainerServiceOrchestratorProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceOrchestratorProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceOrchestratorProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceOrchestratorProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceOrchestratorProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="00dfe-101">コンテナー サービスの orchestrator 用のプロファイル。</span><span class="sxs-lookup"><span data-stu-id="00dfe-101">Profile for the container service orchestrator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceOrchestratorProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00dfe-102">ContainerServiceOrchestratorProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="00dfe-102">Initializes a new instance of the ContainerServiceOrchestratorProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceOrchestratorProfile (Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes orchestratorType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes orchestratorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (orchestratorType As ContainerServiceOrchestratorTypes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile : Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile orchestratorType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="orchestratorType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes" />
      </Parameters>
      <Docs>
        <param name="orchestratorType">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrchestratorType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes OrchestratorType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes OrchestratorType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile.OrchestratorType" />
      <MemberSignature Language="VB.NET" Value="Public Property OrchestratorType As ContainerServiceOrchestratorTypes" />
      <MemberSignature Language="F#" Value="member this.OrchestratorType : Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile.OrchestratorType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orchestratorType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00dfe-103">取得またはコンテナー サービスのクラスター リソースの管理に使用するように、orchestrator を設定します。</span><span class="sxs-lookup"><span data-stu-id="00dfe-103">Gets or sets the orchestrator to use to manage container service cluster resources.</span></span> <span data-ttu-id="00dfe-104">有効な値は群、DCOS、およびカスタムです。</span><span class="sxs-lookup"><span data-stu-id="00dfe-104">Valid values are Swarm, DCOS, and Custom.</span></span>
            <span data-ttu-id="00dfe-105">使用可能な値が含まれます: 'Swarm'、'DCOS'、'Custom'、'Kubernetes'</span><span class="sxs-lookup"><span data-stu-id="00dfe-105">Possible values include: 'Swarm', 'DCOS', 'Custom', 'Kubernetes'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceOrchestratorProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceOrchestratorProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00dfe-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="00dfe-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="00dfe-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="00dfe-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
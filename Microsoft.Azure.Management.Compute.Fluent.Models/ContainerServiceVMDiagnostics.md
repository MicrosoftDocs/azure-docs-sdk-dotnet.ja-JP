<Type Name="ContainerServiceVMDiagnostics" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics">
  <TypeSignature Language="C#" Value="public class ContainerServiceVMDiagnostics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceVMDiagnostics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceVMDiagnostics" />
  <TypeSignature Language="F#" Value="type ContainerServiceVMDiagnostics = class" />
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
            <span data-ttu-id="f846c-101">コンテナー サービスの Vm 上で診断用のプロファイル。</span><span class="sxs-lookup"><span data-stu-id="f846c-101">Profile for diagnostics on the container service VMs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceVMDiagnostics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f846c-102">ContainerServiceVMDiagnostics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f846c-102">Initializes a new instance of the ContainerServiceVMDiagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceVMDiagnostics (bool enabled, string storageUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enabled, string storageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics.#ctor(System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enabled As Boolean, Optional storageUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics : bool * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics (enabled, storageUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="storageUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="f846c-103">かどうか、VM の診断エージェントは、vm がプロビジョニングされます。</span><span class="sxs-lookup"><span data-stu-id="f846c-103">Whether the VM diagnostic agent is provisioned on the VM.</span></span></param>
        <param name="storageUri"><span data-ttu-id="f846c-104">診断の保存先ストレージ アカウントの URI。</span><span class="sxs-lookup"><span data-stu-id="f846c-104">The URI of the storage account where diagnostics are stored.</span></span></param>
        <summary>
            <span data-ttu-id="f846c-105">ContainerServiceVMDiagnostics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f846c-105">Initializes a new instance of the ContainerServiceVMDiagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f846c-106">取得または VM の診断エージェントは、VM でプロビジョニングされているかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f846c-106">Gets or sets whether the VM diagnostic agent is provisioned on the VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public string StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As String" />
      <MemberSignature Language="F#" Value="member this.StorageUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f846c-107">診断の格納場所、ストレージ アカウントの URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="f846c-107">Gets the URI of the storage account where diagnostics are stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceVMDiagnostics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceVMDiagnostics.Validate " />
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
            <span data-ttu-id="f846c-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f846c-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f846c-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f846c-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
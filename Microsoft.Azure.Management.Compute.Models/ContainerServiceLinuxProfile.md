<Type Name="ContainerServiceLinuxProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceLinuxProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceLinuxProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceLinuxProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceLinuxProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29319-101">コンテナー サービスのクラスター内の Linux Vm のプロファイル。</span><span class="sxs-lookup"><span data-stu-id="29319-101">Profile for Linux VMs in the container service cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceLinuxProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29319-102">ContainerServiceLinuxProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29319-102">Initializes a new instance of the ContainerServiceLinuxProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceLinuxProfile (string adminUsername, Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration ssh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string adminUsername, class Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration ssh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.#ctor(System.String,Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (adminUsername As String, ssh As ContainerServiceSshConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile : string * Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile (adminUsername, ssh)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="adminUsername" Type="System.String" />
        <Parameter Name="ssh" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration" />
      </Parameters>
      <Docs>
        <param name="adminUsername"><span data-ttu-id="29319-103">Linux Vm の場合に使用する管理者のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="29319-103">The administrator username to use for Linux VMs.</span></span></param>
        <param name="ssh"><span data-ttu-id="29319-104">Ssh キーの Linux Vm を構成します。</span><span class="sxs-lookup"><span data-stu-id="29319-104">The ssh key configuration for Linux VMs.</span></span></param>
        <summary>
            <span data-ttu-id="29319-105">ContainerServiceLinuxProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29319-105">Initializes a new instance of the ContainerServiceLinuxProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUsername">
      <MemberSignature Language="C#" Value="public string AdminUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.AdminUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUsername As String" />
      <MemberSignature Language="F#" Value="member this.AdminUsername : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.AdminUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUsername")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29319-106">取得または Linux Vm の場合に使用する管理者のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="29319-106">Gets or sets the administrator username to use for Linux VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ssh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration Ssh { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration Ssh" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.Ssh" />
      <MemberSignature Language="VB.NET" Value="Public Property Ssh As ContainerServiceSshConfiguration" />
      <MemberSignature Language="F#" Value="member this.Ssh : Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.Ssh" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ssh")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29319-107">取得または設定、ssh キーの Linux Vm を構成します。</span><span class="sxs-lookup"><span data-stu-id="29319-107">Gets or sets the ssh key configuration for Linux VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceLinuxProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29319-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="29319-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="29319-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="29319-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ContainerServiceSshConfiguration" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration">
  <TypeSignature Language="C#" Value="public class ContainerServiceSshConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceSshConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceSshConfiguration" />
  <TypeSignature Language="F#" Value="type ContainerServiceSshConfiguration = class" />
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
            <span data-ttu-id="80d6d-101">Azure で実行されている Linux ベースの Vm の SSH 構成します。</span><span class="sxs-lookup"><span data-stu-id="80d6d-101">SSH configuration for Linux-based VMs running on Azure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceSshConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="80d6d-102">ContainerServiceSshConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="80d6d-102">Initializes a new instance of the ContainerServiceSshConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceSshConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt; publicKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt; publicKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (publicKeys As IList(Of ContainerServiceSshPublicKey))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration publicKeys" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publicKeys" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt;" />
      </Parameters>
      <Docs>
        <param name="publicKeys"><span data-ttu-id="80d6d-103">Linux ベースの Vm での認証に使用する SSH 公開キーの一覧。</span><span class="sxs-lookup"><span data-stu-id="80d6d-103">the list of SSH public keys used to authenticate with Linux-based VMs.</span></span></param>
        <summary>
            <span data-ttu-id="80d6d-104">ContainerServiceSshConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="80d6d-104">Initializes a new instance of the ContainerServiceSshConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt; PublicKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt; PublicKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration.PublicKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicKeys As IList(Of ContainerServiceSshPublicKey)" />
      <MemberSignature Language="F#" Value="member this.PublicKeys : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration.PublicKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshPublicKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80d6d-105">取得または Linux ベースの Vm での認証に使用する SSH 公開キーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="80d6d-105">Gets or sets the list of SSH public keys used to authenticate with Linux-based VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceSshConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceSshConfiguration.Validate " />
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
            <span data-ttu-id="80d6d-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="80d6d-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="80d6d-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="80d6d-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
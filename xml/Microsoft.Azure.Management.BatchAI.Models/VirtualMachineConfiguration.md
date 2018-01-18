<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="75efc-101">OS イメージの設定です。</span><span class="sxs-lookup"><span data-stu-id="75efc-101">Settings for OS image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="75efc-102">VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="75efc-102">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Management.BatchAI.Models.ImageReference imageReference = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Management.BatchAI.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration : Microsoft.Azure.Management.BatchAI.Models.ImageReference -&gt; Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration imageReference" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.BatchAI.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference"><span data-ttu-id="75efc-103">OS イメージへの参照。</span><span class="sxs-lookup"><span data-stu-id="75efc-103">Reference to OS image.</span></span></param>
        <summary>
            <span data-ttu-id="75efc-104">VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="75efc-104">Initializes a new instance of the VirtualMachineConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.BatchAI.Models.ImageReference with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75efc-105">取得または OS イメージへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="75efc-105">Gets or sets reference to OS image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="75efc-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="75efc-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="75efc-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="75efc-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ContainerServiceCustomProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceCustomProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceCustomProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceCustomProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceCustomProfile = class" />
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
            <span data-ttu-id="ec2dd-101">カスタム コンテナー サービスのクラスターを構成するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="ec2dd-101">Properties to configure a custom container service cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceCustomProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.#ctor" />
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
            <span data-ttu-id="ec2dd-102">ContainerServiceCustomProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ec2dd-102">Initializes a new instance of the ContainerServiceCustomProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceCustomProfile (string orchestrator);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string orchestrator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (orchestrator As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile : string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile orchestrator" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="orchestrator" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="orchestrator"><span data-ttu-id="ec2dd-103">使用するカスタムの orchestrator の名前。</span><span class="sxs-lookup"><span data-stu-id="ec2dd-103">The name of the custom orchestrator to use.</span></span></param>
        <summary>
            <span data-ttu-id="ec2dd-104">ContainerServiceCustomProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ec2dd-104">Initializes a new instance of the ContainerServiceCustomProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Orchestrator">
      <MemberSignature Language="C#" Value="public string Orchestrator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Orchestrator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.Orchestrator" />
      <MemberSignature Language="VB.NET" Value="Public Property Orchestrator As String" />
      <MemberSignature Language="F#" Value="member this.Orchestrator : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.Orchestrator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orchestrator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec2dd-105">取得または使用するカスタムの orchestrator の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ec2dd-105">Gets or sets the name of the custom orchestrator to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceCustomProfile.Validate " />
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
            <span data-ttu-id="ec2dd-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ec2dd-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec2dd-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec2dd-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
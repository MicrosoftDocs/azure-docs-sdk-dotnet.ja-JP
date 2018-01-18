<Type Name="Pipeline" FullName="Microsoft.Azure.Management.DataFactories.Models.Pipeline">
  <TypeSignature Language="C#" Value="public class Pipeline" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Pipeline extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.Pipeline" />
  <TypeSignature Language="VB.NET" Value="Public Class Pipeline" />
  <TypeSignature Language="F#" Value="type Pipeline = class" />
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
            <span data-ttu-id="57a4c-101">パイプラインでは、アクティビティを定義します。</span><span class="sxs-lookup"><span data-stu-id="57a4c-101">A pipeline defines activities.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pipeline ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.Pipeline.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="57a4c-102">パイプライン クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="57a4c-102">Initializes a new instance of the Pipeline class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pipeline (string name, Microsoft.Azure.Management.DataFactories.Models.PipelineProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactories.Models.PipelineProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.Pipeline.#ctor(System.String,Microsoft.Azure.Management.DataFactories.Models.PipelineProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, properties As PipelineProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.Pipeline : string * Microsoft.Azure.Management.DataFactories.Models.PipelineProperties -&gt; Microsoft.Azure.Management.DataFactories.Models.Pipeline" Usage="new Microsoft.Azure.Management.DataFactories.Models.Pipeline (name, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="properties">To be added.</param>
        <summary>
            <span data-ttu-id="57a4c-103">必須の引数でのパイプライン クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="57a4c-103">Initializes a new instance of the Pipeline class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Pipeline.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Pipeline.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57a4c-104">パイプラインの名前。</span><span class="sxs-lookup"><span data-stu-id="57a4c-104">Name of the pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.PipelineProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.PipelineProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Pipeline.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As PipelineProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.DataFactories.Models.PipelineProperties with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Pipeline.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.PipelineProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57a4c-105">パイプラインのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="57a4c-105">Pipeline properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
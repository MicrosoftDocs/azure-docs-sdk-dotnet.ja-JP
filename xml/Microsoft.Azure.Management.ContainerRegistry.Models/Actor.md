<Type Name="Actor" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Actor">
  <TypeSignature Language="C#" Value="public class Actor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Actor extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Actor" />
  <TypeSignature Language="VB.NET" Value="Public Class Actor" />
  <TypeSignature Language="F#" Value="type Actor = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a1157-101">イベントを開始するエージェントです。</span><span class="sxs-lookup"><span data-stu-id="a1157-101">The agent that initiated the event.</span></span> <span data-ttu-id="a1157-102">ほとんどの場合、要求の承認コンテキストから指定できます。</span><span class="sxs-lookup"><span data-stu-id="a1157-102">For most situations, this could be from the authorization context of the request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Actor ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Actor.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a1157-103">アクター クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a1157-103">Initializes a new instance of the Actor class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Actor (string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Actor.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Actor : string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Actor" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Actor name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a1157-104">件名またはイベントを生成した要求コンテキストに関連付けられているユーザー名。</span><span class="sxs-lookup"><span data-stu-id="a1157-104">The subject or username associated with the request context that generated the event.</span></span></param>
        <summary>
            <span data-ttu-id="a1157-105">アクター クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a1157-105">Initializes a new instance of the Actor class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Actor.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Actor.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1157-106">取得または件名またはイベントを生成した要求コンテキストに関連付けられているユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1157-106">Gets or sets the subject or username associated with the request context that generated the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
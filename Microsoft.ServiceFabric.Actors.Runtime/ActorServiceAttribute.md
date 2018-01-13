<Type Name="ActorServiceAttribute" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute">
  <TypeSignature Language="C#" Value="public sealed class ActorServiceAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorServiceAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorServiceAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ActorServiceAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Class)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5c31a-101">アクター サービスのプロパティを構成できるようにする属性を表します。</span><span class="sxs-lookup"><span data-stu-id="5c31a-101">Represents the attributes that allows configuring the properties of the actor service.</span></span> <span data-ttu-id="5c31a-102">属性は、アクターの型に適用されます。</span><span class="sxs-lookup"><span data-stu-id="5c31a-102">The attribute is applied on the actor type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c31a-103">ActorServiceAttribute クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c31a-103">Initializes a new instance of the ActorServiceAttribute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c31a-104">取得またはアクター サービスの相対名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c31a-104">Gets or sets the relative name of the actor service.</span></span> <span data-ttu-id="5c31a-105">この名前は、アクター サービスの完全な名前を提供するアプリケーションの名前にまとめられます。</span><span class="sxs-lookup"><span data-stu-id="5c31a-105">This name will be combined with the application name to provide the full name of the actor service.</span></span> 
            </summary>
        <value><span data-ttu-id="5c31a-106">アプリケーション名の相対アクター サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="5c31a-106">The name of the actor service relative to the application name.</span></span></value>
        <remarks>
          <para>
                <span data-ttu-id="5c31a-107">既定では、アクター サービス名はアクター インターフェイスの型から派生 (<see cref="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />)。</span><span class="sxs-lookup"><span data-stu-id="5c31a-107">By default, the actor service name is derived from the type of the actor interface (<see cref="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />).</span></span> <span data-ttu-id="5c31a-108">ただし、複数のアクターによってアクター インターフェイスを実装すると場合、派生型を含む名前を特定できませんアクター インターフェイスから明確な方法で。</span><span class="sxs-lookup"><span data-stu-id="5c31a-108">However, in case when an actor interface is implemented by more than one actor, including by a derived type, the name cannot be determined from the actor interface in an unambiguous manner.</span></span> <span data-ttu-id="5c31a-109">このプロパティを使用して、アクター サービスの名前を構成する必要がありますその場合は、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />です。</span><span class="sxs-lookup"><span data-stu-id="5c31a-109">In that case, the name of the actor service must be configured using this property of the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</span></span>
                </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
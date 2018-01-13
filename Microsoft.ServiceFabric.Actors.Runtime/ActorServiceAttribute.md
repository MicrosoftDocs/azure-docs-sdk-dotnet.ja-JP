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
            アクター サービスのプロパティを構成できるようにする属性を表します。 属性は、アクターの型に適用されます。
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
            ActorServiceAttribute クラスの新しいインスタンスを初期化します。
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
            取得またはアクター サービスの相対名を設定します。 この名前は、アクター サービスの完全な名前を提供するアプリケーションの名前にまとめられます。 
            </summary>
        <value>アプリケーション名の相対アクター サービスの名前。</value>
        <remarks>
          <para>
                既定では、アクター サービス名はアクター インターフェイスの型から派生 (<see cref="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />)。 ただし、複数のアクターによってアクター インターフェイスを実装すると場合、派生型を含む名前を特定できませんアクター インターフェイスから明確な方法で。 このプロパティを使用して、アクター サービスの名前を構成する必要がありますその場合は、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />です。
                </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
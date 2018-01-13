<Type Name="ActorTypeExtensions" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions">
  <TypeSignature Language="C#" Value="public static class ActorTypeExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActorTypeExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActorTypeExtensions" />
  <TypeSignature Language="F#" Value="type ActorTypeExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            アクターの種類の拡張メソッドが含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetActorEventInterfaces">
      <MemberSignature Language="C#" Value="public static Type[] GetActorEventInterfaces (this Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Type[] GetActorEventInterfaces(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorEventInterfaces(System.Type)" />
      <MemberSignature Language="F#" Value="static member GetActorEventInterfaces : Type -&gt; Type[]" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorEventInterfaces type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="type">クラスの実装のアクターの型。</param>
        <summary>
            アクターのイベント インターフェイスがアクター クラスによって実装を取得します。
            </summary>
        <returns>型を実装しているアクター イベント インターフェイスを格納する配列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActorInterfaces">
      <MemberSignature Language="C#" Value="public static Type[] GetActorInterfaces (this Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Type[] GetActorInterfaces(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorInterfaces(System.Type)" />
      <MemberSignature Language="F#" Value="static member GetActorInterfaces : Type -&gt; Type[]" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorInterfaces type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="type">クラスの実装のアクターの型。</param>
        <summary>
            アクター クラスによって実装されたアクター インターフェイスを取得します。
            </summary>
        <returns>型を実装しているアクターのインターフェイスを格納する配列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsActor">
      <MemberSignature Language="C#" Value="public static bool IsActor (this Type actorType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsActor(class System.Type actorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActor(System.Type)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsActor (actorType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsActor : Type -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActor actorType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="actorType">型の実装するアクターです。</param>
        <summary>
            ActorType がアクターであるかどうかの値を示します。
            </summary>
        <returns>場合は true、 <see cref="P:System.Type.BaseType" /> actorType は、 <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsActorInterface">
      <MemberSignature Language="C#" Value="public static bool IsActorInterface (this Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsActorInterface(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActorInterface(System.Type)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsActorInterface (actorInterfaceType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsActorInterface : Type -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActorInterface actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType">アクターのインターフェイスの型。</param>
        <summary>
            インターフェイスの型がアクター インターフェイスであるかどうかを示します。
            </summary>
        <returns>条件を満たす、actorInterfaceType がインターフェイスの場合のみを実装する<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />または (<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />と<see cref="T:Microsoft.ServiceFabric.Actors.IActorEventPublisher" />)。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRemindableActor">
      <MemberSignature Language="C#" Value="public static bool IsRemindableActor (this Type actorType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsRemindableActor(class System.Type actorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsRemindableActor(System.Type)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsRemindableActor (actorType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsRemindableActor : Type -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsRemindableActor actorType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="actorType">型の実装するアクターです。</param>
        <summary>
            アクター型が実装するかどうかの値を示します<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />インターフェイスです。
            </summary>
        <returns>場合は true、<paramref name="actorType" />を実装する<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />インターフェイスです。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
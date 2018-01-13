<Type Name="ActorTypeInformation" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation">
  <TypeSignature Language="C#" Value="public sealed class ActorTypeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorTypeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorTypeInformation" />
  <TypeSignature Language="F#" Value="type ActorTypeInformation = class" />
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
            アクターを実装する型についてを説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorTypeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ActorTypeInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventInterfaceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Type&gt; EventInterfaceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; EventInterfaceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.EventInterfaceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventInterfaceTypes As IEnumerable(Of Type)" />
      <MemberSignature Language="F#" Value="member this.EventInterfaceTypes : seq&lt;Type&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.EventInterfaceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Type&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクターにアクター クラスを実装するイベント インターフェイスを取得します。
            </summary>
        <value>アクター クラスを実装しているアクター イベント インターフェイスの反復処理に使用できる列挙子。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation Get (Type actorType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation Get(class System.Type actorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.Get(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Get (actorType As Type) As ActorTypeInformation" />
      <MemberSignature Language="F#" Value="static member Get : Type -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.Get actorType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorType">ActorTypeInforamtion を作成するアクターを実装するクラスの型。</param>
        <summary>
            作成、 <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> actorType からです。
            </summary>
        <returns>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />actorType から作成されます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>ときに<see cref="P:System.Type.BaseType" />actorType が型ではありません<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />です。</para>
          <para>ActorType がから派生したインターフェイスを実装しないとき<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />抽象としてマークされていないとします。</para>
          <para>ActorType がから派生する 1 つ以上のインターフェイスを実装すると<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />はありませんが、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />です。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ImplementationType">
      <MemberSignature Language="C#" Value="public Type ImplementationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ImplementationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ImplementationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImplementationType As Type" />
      <MemberSignature Language="F#" Value="member this.ImplementationType : Type" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ImplementationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクターを実装するクラスの種類を取得します。
            </summary>
        <value><see cref="T:System.Type" />のアクターを実装するクラス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Type&gt; InterfaceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; InterfaceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.InterfaceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InterfaceTypes As IEnumerable(Of Type)" />
      <MemberSignature Language="F#" Value="member this.InterfaceTypes : seq&lt;Type&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.InterfaceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Type&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクターから派生するインターフェイスの種類を取得<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />アクター クラスによって実装されるとします。
            </summary>
        <value>アクター インターフェイス型を反復処理に使用できる列挙子。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAbstract">
      <MemberSignature Language="C#" Value="public bool IsAbstract { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAbstract" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsAbstract" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAbstract As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAbstract : bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsAbstract" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クラスの実装のアクターが抽象であるかどうかは、値を取得します。
            </summary>
        <value>クラスの実装のアクターが抽象、それ以外の場合は false である場合は true です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRemindable">
      <MemberSignature Language="C#" Value="public bool IsRemindable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRemindable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsRemindable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRemindable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRemindable : bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsRemindable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクター クラスを実装するかどうかの値を取得<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />です。
            </summary>
        <value>アクター クラスを実装する場合は true。 <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />、それ以外の場合は false。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public string ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ServiceName" />
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
            使用して指定されている場合は、サービス名を取得<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />アクター クラスです。
            </summary>
        <value>使用して指定されている場合、サービス名<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />アクター クラスの属性を使用しない場合は null です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatePersistence">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.StatePersistence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatePersistence As StatePersistence" />
      <MemberSignature Language="F#" Value="member this.StatePersistence : Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.StatePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" />アクターの状態の永続性の種類を表す列挙型。
            </summary>
        <value><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" />アクターの状態の永続性の種類を表示します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public static bool TryGet (Type actorType, out Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGet(class System.Type actorType, [out] class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation&amp; actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.TryGet(System.Type,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryGet (actorType As Type, ByRef actorTypeInformation As ActorTypeInformation) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryGet : Type *  -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.TryGet (actorType, actorTypeInformation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" />
        <Parameter Name="actorTypeInformation" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="actorType">ActorTypeInforamtion を作成するアクターを実装するクラスの型。</param>
        <param name="actorTypeInformation">このメソッドが戻るときに含まれています ActorTypeInformation、actorType から ActorTypeInformation の作成が成功した場合または null 場合は、作成に失敗しました。
            ActorType パラメーターが null またはアクターを実装していない場合、作成は失敗します。</param>
        <summary>
            作成、 <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> actorType からです。
            </summary>
        <returns>actorType; の ActorTypeInformation を正常に作成する場合は true。それ以外の場合は false です。</returns>
        <remarks>
          <para>ActorType から ActorTypeInformation の作成に失敗します。 </para>
          <para>1. <see cref="P:System.Type.BaseType" />actorType が型ではありません<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />です。</para>
          <para>2. actorType がから派生したインターフェイスを実装しません<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />抽象としてマークされていないとします。</para>
          <para>3. 派生する 1 つ以上のインターフェイスを実装する actorType<see cref="T:Microsoft.ServiceFabric.Actors.IActor" />必要はありません<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />です。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ActorServiceSettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings">
  <TypeSignature Language="C#" Value="public sealed class ActorServiceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorServiceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorServiceSettings" />
  <TypeSignature Language="F#" Value="type ActorServiceSettings = class" />
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
            アクター サービスの動作を構成する設定。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ActorServiceSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorConcurrencySettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings ActorConcurrencySettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings ActorConcurrencySettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorConcurrencySettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorConcurrencySettings As ActorConcurrencySettings" />
      <MemberSignature Language="F#" Value="member this.ActorConcurrencySettings : Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorConcurrencySettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクターをベースにする同時実行のロックを構成する設定を設定します。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />アクター サービス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorGarbageCollectionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings ActorGarbageCollectionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings ActorGarbageCollectionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorGarbageCollectionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorGarbageCollectionSettings As ActorGarbageCollectionSettings" />
      <MemberSignature Language="F#" Value="member this.ActorGarbageCollectionSettings : Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorGarbageCollectionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクター サービスのガベージ コレクションの設定を設定します。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings" />アクター サービス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReminderSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings ReminderSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings ReminderSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ReminderSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ReminderSettings As ReminderSettings" />
      <MemberSignature Language="F#" Value="member this.ReminderSettings : Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ReminderSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または通知の動作を構成する設定を設定します。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings" />アクター サービス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
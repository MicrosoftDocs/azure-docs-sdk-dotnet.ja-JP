<Type Name="ActorGarbageCollectionSettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings">
  <TypeSignature Language="C#" Value="public sealed class ActorGarbageCollectionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorGarbageCollectionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorGarbageCollectionSettings" />
  <TypeSignature Language="F#" Value="type ActorGarbageCollectionSettings = class" />
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
            アクター サービスのガベージ コレクションの動作を構成する設定を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorGarbageCollectionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            入力引数の値を持つ ActorGarbageCollectionSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorGarbageCollectionSettings (long idleTimeoutInSeconds, long scanIntervalInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 idleTimeoutInSeconds, int64 scanIntervalInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (idleTimeoutInSeconds As Long, scanIntervalInSeconds As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings : int64 * int64 -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings" Usage="new Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings (idleTimeoutInSeconds, scanIntervalInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="idleTimeoutInSeconds" Type="System.Int64" />
        <Parameter Name="scanIntervalInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="idleTimeoutInSeconds">ガベージに含まれていないするアクターの収集を使用する前に待機する時間間隔。</param>
        <param name="scanIntervalInSeconds">アクターのガベージ コレクション スキャンを実行する時間間隔。</param>
        <summary>
            ActorGarbageCollectionSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>IdleTimeoutInSeconds が場合 0 以下です。</para>
          <para>ScanIntervalInSeconds が場合 0 以下です。</para>
          <para>IdleTimeoutInSeconds が場合 scanIntervalInSeconds より小さいです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long IdleTimeoutInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IdleTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.IdleTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdleTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInSeconds : int64" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.IdleTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ガベージが使用されていないするアクターを収集する前に待機する時間間隔を取得します。
            </summary>
        <value>時間間隔<see cref="T:System.Int64" />ガベージに含まれていないするアクターの収集を使用する前に待機します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScanIntervalInSeconds">
      <MemberSignature Language="C#" Value="public long ScanIntervalInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScanIntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.ScanIntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScanIntervalInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.ScanIntervalInSeconds : int64" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.ScanIntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクターのガベージ コレクション スキャンを実行する時間間隔を取得します。
            </summary>
        <value>時間間隔<see cref="T:System.Int64" />アクター ガベージ コレクション スキャンを実行します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
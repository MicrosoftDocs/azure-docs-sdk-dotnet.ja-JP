<Type Name="TargetReplicaSelector" FullName="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector">
  <TypeSignature Language="C#" Value="public enum TargetReplicaSelector" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TargetReplicaSelector extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
  <TypeSignature Language="VB.NET" Value="Public Enum TargetReplicaSelector" />
  <TypeSignature Language="F#" Value="type TargetReplicaSelector = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            この列挙体は、どのように、ターゲット レプリカまたはインスタンスを選択する特定のパーティション用の通信チャネルを作成するときに指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            これには、この列挙型の既定のオプションを指定します。
            サービス パーティションがステートフルの場合は、プライマリ レプリカにその通信チャネルを確立する必要がありますを示します。
            サービス パーティションがステートレスの場合は、ランダム ステートレスなインスタンスに通信チャネルを確立する必要があることを示します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PrimaryReplica">
      <MemberSignature Language="C#" Value="PrimaryReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector PrimaryReplica = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />
      <MemberSignature Language="VB.NET" Value="PrimaryReplica" />
      <MemberSignature Language="F#" Value="PrimaryReplica = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            これには、ステートフルなサービスのパーティションに対して、この列挙型の既定値を指定します。 これは、プライマリ レプリカに通信チャネルを確立する必要があることを示します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomInstance">
      <MemberSignature Language="C#" Value="RandomInstance" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomInstance = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomInstance" />
      <MemberSignature Language="VB.NET" Value="RandomInstance" />
      <MemberSignature Language="F#" Value="RandomInstance = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomInstance" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            これには、ステートレス サービスのパーティションに対して、この列挙型の既定値を指定します。 これは、ランダムのステートレス インスタンスへの通信チャネルを確立する必要があることを示します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomReplica">
      <MemberSignature Language="C#" Value="RandomReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomReplica = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomReplica" />
      <MemberSignature Language="VB.NET" Value="RandomReplica" />
      <MemberSignature Language="F#" Value="RandomReplica = 1" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            ステートフルなサービス パーティション、これには、通信チャネルを確立できるので選択された任意のレプリカを示します - ランダムな (つまり、) プライマリまたはセカンダリ。
            これはステートレスなサービスのパーティションに対して有効ではありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomSecondaryReplica">
      <MemberSignature Language="C#" Value="RandomSecondaryReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomSecondaryReplica = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomSecondaryReplica" />
      <MemberSignature Language="VB.NET" Value="RandomSecondaryReplica" />
      <MemberSignature Language="F#" Value="RandomSecondaryReplica = 2" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomSecondaryReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            ステートフルなサービスでは、パーティションの通信チャネルを確立できるのランダムに選択した任意のセカンダリ レプリカを示します。
            これはステートレスなサービスのパーティションに対して有効ではありません。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
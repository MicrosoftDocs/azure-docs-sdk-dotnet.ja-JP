<Type Name="ReplicaRole" FullName="System.Fabric.ReplicaRole">
  <TypeSignature Language="C#" Value="public enum ReplicaRole" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReplicaRole extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicaRole" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReplicaRole" />
  <TypeSignature Language="F#" Value="type ReplicaRole = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>ステートフル サービス レプリカのロールを示します。 </para>
    </summary>
    <remarks>
      <para>Service Fabric には、によっては、現在実行して、どのような役割サービスのレプリカから別の動作が必要です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActiveSecondary">
      <MemberSignature Language="C#" Value="ActiveSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole ActiveSecondary = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.ActiveSecondary" />
      <MemberSignature Language="VB.NET" Value="ActiveSecondary" />
      <MemberSignature Language="F#" Value="ActiveSecondary = 4" Usage="System.Fabric.ReplicaRole.ActiveSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>プライマリ レプリカから状態の更新を受け取る、適用、および承認を返信するセット内のレプリカを指します。 セカンダリ レプリカは、レプリカ セットの書き込みクォーラムに参加する必要があります。 同時に設定、レプリカで複数のアクティブなセカンダリ レプリカがあります。 アクティブなセカンダリ レプリカの数は、信頼性サブシステムを管理する必要があります構成可能です。  </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="IdleSecondary">
      <MemberSignature Language="C#" Value="IdleSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole IdleSecondary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.IdleSecondary" />
      <MemberSignature Language="VB.NET" Value="IdleSecondary" />
      <MemberSignature Language="F#" Value="IdleSecondary = 3" Usage="System.Fabric.ReplicaRole.IdleSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>アクティブなセカンダリ レプリカになるを準備する、プライマリ レプリカから状態転送を受信したセットには、レプリカを指します。 同時に設定、レプリカで複数のアイドルなセカンダリ レプリカがあります。 アイドルなセカンダリ レプリカは、書き込みクォーラムの一部としてはカウントされません。 </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.ReplicaRole.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>レプリカにレプリカ セットに関して責任がないことを指定します。</para>
        </summary>
        <remarks>
          <para>ときに<see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />このロールを示すこのレプリカに関連付けられているすべての永続的な状態を削除しても安全です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="Primary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole Primary = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.Primary" />
      <MemberSignature Language="VB.NET" Value="Primary" />
      <MemberSignature Language="F#" Value="Primary = 2" Usage="System.Fabric.ReplicaRole.Primary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>どのすべての読み取りと書き込みのセットの操作は強力な一貫性セマンティクスを適用するために完全なレプリカを指します。 読み取り操作は、レプリカ セット内のレプリカのクォーラムの書き込み操作を承認する必要があります中に、プライマリ レプリカによって直接処理されます。 できるだけ 1 つのプライマリ レプリカで、レプリカが同時に設定します。 </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="System.Fabric.ReplicaRole.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>レプリカが作成される初期の役割を示します。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>
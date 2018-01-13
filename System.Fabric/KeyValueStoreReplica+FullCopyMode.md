<Type Name="KeyValueStoreReplica+FullCopyMode" FullName="System.Fabric.KeyValueStoreReplica+FullCopyMode">
  <TypeSignature Language="C#" Value="public enum KeyValueStoreReplica.FullCopyMode" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed KeyValueStoreReplica/FullCopyMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica.FullCopyMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum KeyValueStoreReplica.FullCopyMode" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica.FullCopyMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>新しいセカンダリ レプリカ (完全なコピー) を構築するときに使用する動作を指定します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>クラスター マニフェストで指定された完全なコピー モードが使用されます。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Logical">
      <MemberSignature Language="C#" Value="Logical" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Logical = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Logical" />
      <MemberSignature Language="VB.NET" Value="Logical" />
      <MemberSignature Language="F#" Value="Logical = 2" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Logical" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>完全なコピーは、すべてのデータベースの内容を読み取り、独自のデータベースに対する再生のためのセカンダリ レプリカに送信して実行されます。 このモードでは、実行時間の長いトランザクションでは、プライマリに期間のビルドを開く必要があります、ためのみお勧め小規模なデータベースやサービスの書き込みの低アクティビティとします。 このモードでは通常、修正される初期化した後など、変化するデータベースのパラメーターは、<see cref="P:System.Fabric.LocalEseStoreSettings.DatabasePageSizeInKB" />と<see cref="P:System.Fabric.LocalEseStoreSettings.LogFileSizeInKB" />です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Physical">
      <MemberSignature Language="C#" Value="Physical" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Physical = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Physical" />
      <MemberSignature Language="VB.NET" Value="Physical" />
      <MemberSignature Language="F#" Value="Physical = 1" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Physical" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>完全なコピーがプライマリ レプリカ データベースのバックアップを行うと、復元するためのセカンダリ レプリカへの物理データベース ファイルを送信して実行されます。 これは、推奨されると、既定のモード。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rebuild">
      <MemberSignature Language="C#" Value="Rebuild" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode Rebuild = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.FullCopyMode.Rebuild" />
      <MemberSignature Language="VB.NET" Value="Rebuild" />
      <MemberSignature Language="F#" Value="Rebuild = 3" Usage="System.Fabric.KeyValueStoreReplica.FullCopyMode.Rebuild" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>セカンダリ上の新しいデータベースのプライマリ インデックス順序ですべてのデータベースのコンテンツを再生するは追加の手順が、物理的なコピーでは、完全なコピーが実行されます。 このモードでは、初期化後は、固定は、通常は、余分な再生手順のための物理的または論理的のいずれかのビルドよりも長くかかりますデータベース パラメーターを変更することもできます。 再生を後に、プライマリ インデックスの順序で挿入が発生した後で、最終的なデータ レイアウトが最適です。 現在 Linux ではサポートされません。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>
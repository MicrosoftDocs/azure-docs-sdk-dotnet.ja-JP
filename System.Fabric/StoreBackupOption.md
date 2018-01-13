<Type Name="StoreBackupOption" FullName="System.Fabric.StoreBackupOption">
  <TypeSignature Language="C#" Value="public enum StoreBackupOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StoreBackupOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.StoreBackupOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum StoreBackupOption" />
  <TypeSignature Language="F#" Value="type StoreBackupOption = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            キー値ストアのバックアップ オプション。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Full">
      <MemberSignature Language="C#" Value="Full" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.StoreBackupOption Full = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.StoreBackupOption.Full" />
      <MemberSignature Language="VB.NET" Value="Full" />
      <MemberSignature Language="F#" Value="Full = 1" Usage="System.Fabric.StoreBackupOption.Full" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            キー値ストアの完全バックアップ。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Incremental">
      <MemberSignature Language="C#" Value="Incremental" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.StoreBackupOption Incremental = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.StoreBackupOption.Incremental" />
      <MemberSignature Language="VB.NET" Value="Incremental" />
      <MemberSignature Language="F#" Value="Incremental = 2" Usage="System.Fabric.StoreBackupOption.Incremental" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            キー値ストアの増分バックアップです。 つまり、ログ ファイルのみ、最後のフルまたは増分バックアップがバックアップされるため、作成します。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="TruncateLogsOnly">
      <MemberSignature Language="C#" Value="TruncateLogsOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.StoreBackupOption TruncateLogsOnly = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />
      <MemberSignature Language="VB.NET" Value="TruncateLogsOnly" />
      <MemberSignature Language="F#" Value="TruncateLogsOnly = 3" Usage="System.Fabric.StoreBackupOption.TruncateLogsOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>
            すべてのバックアップ ファイルを作成しなくても、キー値ストアのトランザクション ログの切り捨てを行うためのオプションです。        
            </para>
        </summary>
        <remarks>
            これは、増分バックアップを有効にすると、セカンダリ レプリカでバックアップ ファイルの作成を回避するのに便利です。
            増分バックアップが有効な場合は、ディスク領域がいっぱいのキー値ストアのトランザクション ログでします。
            これを防ぐためには、頻繁にバックアップを作成する必要はします。 ただし、セカンダリ レプリカでバックアップを作成できない可能性がありますキー値ストア サービスによっては便利です。 これらのサービスでは、バックアップ ディレクトリを破棄することに対処しなければなりませんもします。 このオプションを使用すると場合、クリーンアップは、トランザクション ログ バックアップ ファイルを作成します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
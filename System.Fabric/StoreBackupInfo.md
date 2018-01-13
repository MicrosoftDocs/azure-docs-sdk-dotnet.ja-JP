<Type Name="StoreBackupInfo" FullName="System.Fabric.StoreBackupInfo">
  <TypeSignature Language="C#" Value="public sealed class StoreBackupInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StoreBackupInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.StoreBackupInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StoreBackupInfo" />
  <TypeSignature Language="F#" Value="type StoreBackupInfo = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>呼び出すことによって作成されたバックアップに関する情報を提供<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoreBackupInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.StoreBackupInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupChainId">
      <MemberSignature Language="C#" Value="public Guid BackupChainId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid BackupChainId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupChainId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupChainId As Guid" />
      <MemberSignature Language="F#" Value="member this.BackupChainId : Guid" Usage="System.Fabric.StoreBackupInfo.BackupChainId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            このバックアップが所属するバックアップ チェーンの ID を取得します。 バックアップのチェーンには、1 つの完全バックアップが含まれています。 と継続的な増分バックアップしてから開始の 0 個以上の完全バックアップ。 
            </para>
        </summary>
        <value>
          <para>バックアップ チェーンの ID。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupFolder">
      <MemberSignature Language="C#" Value="public string BackupFolder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupFolder" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupFolder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupFolder As String" />
      <MemberSignature Language="F#" Value="member this.BackupFolder : string" Usage="System.Fabric.StoreBackupInfo.BackupFolder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>バックアップを作成したフォルダーを取得します。</para>
        </summary>
        <value>
          <para>バックアップ フォルダー</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupIndex">
      <MemberSignature Language="C#" Value="public long BackupIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BackupIndex" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupIndex As Long" />
      <MemberSignature Language="F#" Value="member this.BackupIndex : int64" Usage="System.Fabric.StoreBackupInfo.BackupIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            このバックアップが属している、バックアップ チェーン内には、このバックアップのインデックスを取得します。
            バックアップのチェーンを含む 1 つの完全バックアップと 0 個以上の継続的な増分バックアップです。
            完全バックアップから開始します。 完全バックアップでは、チェーンを開始、ため、バックアップのインデックスは常に 0 にします。
            </para>
        </summary>
        <value>
          <para>現在のバックアップのバックアップのインデックス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupOption">
      <MemberSignature Language="C#" Value="public System.Fabric.StoreBackupOption BackupOption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.StoreBackupOption BackupOption" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StoreBackupInfo.BackupOption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupOption As StoreBackupOption" />
      <MemberSignature Language="F#" Value="member this.BackupOption : System.Fabric.StoreBackupOption" Usage="System.Fabric.StoreBackupInfo.BackupOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StoreBackupOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>使用するバックアップのオプションを取得します。</para>
        </summary>
        <value>
          <para>バックアップ オプションの使用</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.StoreBackupInfo.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storeBackupInfo.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>返します、<see cref="T:System.String" />このインスタンスを表す</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.String" />このインスタンスを表す</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="LocalEseStoreSettings" FullName="System.Fabric.LocalEseStoreSettings">
  <TypeSignature Language="C#" Value="public sealed class LocalEseStoreSettings : System.Fabric.LocalStoreSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LocalEseStoreSettings extends System.Fabric.LocalStoreSettings" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.LocalEseStoreSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LocalEseStoreSettings&#xA;Inherits LocalStoreSettings" />
  <TypeSignature Language="F#" Value="type LocalEseStoreSettings = class&#xA;    inherit LocalStoreSettings" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.LocalStoreSettings</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>ESE ローカル ストア用のオプションの設定を表します。</para>
    </summary>
    <remarks>
      <para>(V=exchg.10).aspx をハイパーリンク"http://msdn.microsoft.com/library/gg294139"http://msdn.microsoft.com/library/gg294139 (v=exchg.10).aspx ESE パラメーターのドキュメントについてを参照してくださいします。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalEseStoreSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LocalEseStoreSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.LocalEseStoreSettings" /> クラスの新しいインスタンスを作成して初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompactionThresholdInMB">
      <MemberSignature Language="C#" Value="public int CompactionThresholdInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CompactionThresholdInMB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.CompactionThresholdInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property CompactionThresholdInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.CompactionThresholdInMB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.CompactionThresholdInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または開くときに発生するオフラインの圧縮のデータベースの最小ファイル サイズを示す値を設定します。
            </summary>
        <value>
            しきい値を mb 単位で返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabasePageSizeInKB">
      <MemberSignature Language="C#" Value="public int DatabasePageSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DatabasePageSizeInKB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.DatabasePageSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabasePageSizeInKB As Integer" />
      <MemberSignature Language="F#" Value="member this.DatabasePageSizeInKB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.DatabasePageSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ESE ローカル ストアに JET_paramDatabasePageSize に直接マップされます。
            </summary>
        <value>
            (KB 単位) には、データベースのページ サイズを返します。
            </value>
        <remarks>
            指定されたデータベースのページ サイズは、新しく作成されたデータベースにのみ適用されます。 既存のデータベースは、この設定と異なる場合に作成されたデータベースのページ サイズを使用し続けます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DbFolderPath">
      <MemberSignature Language="C#" Value="public string DbFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DbFolderPath" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.DbFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property DbFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.DbFolderPath : string with get, set" Usage="System.Fabric.LocalEseStoreSettings.DbFolderPath" />
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
          <para>取得またはローカル ストアのファイルを含むファイルのパスを設定します。</para>
        </summary>
        <value>
          <para>ローカル ストアのファイルを含むファイル パスです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefragThresholdInMB">
      <MemberSignature Language="C#" Value="public int DefragThresholdInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DefragThresholdInMB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.DefragThresholdInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property DefragThresholdInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.DefragThresholdInMB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.DefragThresholdInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバック グラウンドの発生をオンラインでの最適化のデータベースの最小論理サイズを示す値を設定します。
            </summary>
        <value>
            しきい値を mb 単位で返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIncrementalBackup">
      <MemberSignature Language="C#" Value="public bool EnableIncrementalBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableIncrementalBackup" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableIncrementalBackup As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableIncrementalBackup : bool with get, set" Usage="System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または使用するための増分バックアップ機能が有効になっているかどうかを示す値を設定します。</para>
        </summary>
        <value>
            返します<languageKeyword>true</languageKeyword>増分バックアップが有効になっている、それ以外の場合は<languageKeywork>false</languageKeywork>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableOverwriteOnUpdate">
      <MemberSignature Language="C#" Value="public bool EnableOverwriteOnUpdate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableOverwriteOnUpdate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.EnableOverwriteOnUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableOverwriteOnUpdate As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableOverwriteOnUpdate : bool with get, set" Usage="System.Fabric.LocalEseStoreSettings.EnableOverwriteOnUpdate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            有効、インプレース (挿入/削除) に対する値の置換更新操作中にします。 ESE ローカル ストアに JET_bitSetOverwriteLV にマップされます。
            </summary>
        <value>
            返します<languageKeyword>true</languageKeyword>場合に上書き更新プログラムが有効になっている、それ以外の<languageKeywork>false</languageKeywork>です。
            </value>
        <remarks>
            この設定を有効にするは、特定のアクセス パターンを論理データのサイズが同じ場合でも、ディスクに拡張する ESE データベース ファイルが原因である場合に便利です。 たとえば、多数のロールバックを取得するトランザクションまたは一連の更新が行われていると、他のトランザクションが開いたまま中に、一部のトランザクションによって行われた更新します。 
            
            この設定を有効にすることがあります増大するバージョン ストアの使用法との値に注意してください<see cref="P:System.Fabric.LocalEseStoreSettings.MaxVerPages" />に増やす必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IntrinsicValueThresholdInBytes">
      <MemberSignature Language="C#" Value="public int IntrinsicValueThresholdInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 IntrinsicValueThresholdInBytes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.IntrinsicValueThresholdInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property IntrinsicValueThresholdInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.IntrinsicValueThresholdInBytes : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.IntrinsicValueThresholdInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または更新プログラムが現在 JET_bitSetIntrinsicLV フラグで発生する場合は最大値のサイズを示す値を設定します。 負の値に設定すると、ESE の既定値は 1024 バイトが使用されます。
            </summary>
        <value>
            しきい値 (バイト単位) が返されます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.LocalEseStoreSettings LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.LocalEseStoreSettings LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LocalEseStoreSettings.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.LocalEseStoreSettings" Usage="System.Fabric.LocalEseStoreSettings.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalEseStoreSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">このコードが実行されているアクティベーション コンテキスト。 取得した<see cref="T:System.Fabric.FabricRuntime" />です。</param>
        <param name="configPackageName">名前 (サービス マニフェストで指定)、構成パッケージの設定を含む、読み込めません。</param>
        <param name="sectionName">読み込む設定を含む指定した構成パッケージ内の Settings.xml セクションの名前です。</param>
        <summary>
            アプリケーションの構成パッケージから読み込まれたプロパティの値で初期化されたこのクラスのインスタンスを作成する便利なメソッド。
            </summary>
        <returns>初期化されている設定オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogBufferSizeInKB">
      <MemberSignature Language="C#" Value="public int LogBufferSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogBufferSizeInKB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.LogBufferSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property LogBufferSizeInKB As Integer" />
      <MemberSignature Language="F#" Value="member this.LogBufferSizeInKB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.LogBufferSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ESE ローカル ストアに JET_paramLogBuffers にマップされます。 KB から 512 バイト (セクター サイズのボリューム) のマッピングへの変換があります。</para>
        </summary>
        <value>
          <para>ログ バッファ サイズ (KB 単位)。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogFileSizeInKB">
      <MemberSignature Language="C#" Value="public int LogFileSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogFileSizeInKB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.LogFileSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property LogFileSizeInKB As Integer" />
      <MemberSignature Language="F#" Value="member this.LogFileSizeInKB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.LogFileSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ESE ローカル ストアに JET_paramLogFileSize に直接マップされます。
            </para>
        </summary>
        <value>
          <para>ログ ファイルのサイズ (KB 単位)。</para>
        </value>
        <remarks>
            指定されたログ ファイルのサイズは、新しく作成されたデータベースにのみ適用されます。 既存のデータベースは、この設定と異なる場合に作成されたログ ファイルのサイズを使用し続けます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAsyncCommitDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxAsyncCommitDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxAsyncCommitDelay" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxAsyncCommitDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAsyncCommitDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxAsyncCommitDelay : TimeSpan with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxAsyncCommitDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ローカルのコミットが実行されるときの JetCommitTransaction2() ESE API 呼び出しで cmsecDurableCommit パラメーターに直接マップされます。
            </para>
        </summary>
        <value>
          <para>持続性のある低速コミット時間です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCacheSizeInMB">
      <MemberSignature Language="C#" Value="public int MaxCacheSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxCacheSizeInMB" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxCacheSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCacheSizeInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxCacheSizeInMB : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxCacheSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ESE ローカル ストアに JET_paramCacheSizeMax に直接マップされます。
            </summary>
        <value>
            データベースの最大キャッシュ サイズを mb 単位で返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCursors">
      <MemberSignature Language="C#" Value="public int MaxCursors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxCursors" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxCursors" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCursors As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxCursors : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxCursors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ESE ローカル ストアに JET_paramMaxCursors に直接マップされます。
            </para>
        </summary>
        <value>
          <para>許可されているデータベースのカーソルの最大数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDefragFrequencyInMinutes">
      <MemberSignature Language="C#" Value="public int MaxDefragFrequencyInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDefragFrequencyInMinutes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxDefragFrequencyInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDefragFrequencyInMinutes As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDefragFrequencyInMinutes : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxDefragFrequencyInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または定期的なオンラインでの最適化の頻度を示す値を設定します。
            </summary>
        <value>
            頻度を分単位で返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxVerPages">
      <MemberSignature Language="C#" Value="public int MaxVerPages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxVerPages" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LocalEseStoreSettings.MaxVerPages" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxVerPages As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxVerPages : int with get, set" Usage="System.Fabric.LocalEseStoreSettings.MaxVerPages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ESE ローカル ストアに JET_paramMaxVerPages に直接マップされます。
            </para>
        </summary>
        <value>
          <para>許可されているバージョンのページの最大数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
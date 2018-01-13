<Type Name="ExeHostEntryPointDescription" FullName="System.Fabric.Description.ExeHostEntryPointDescription">
  <TypeSignature Language="C#" Value="public sealed class ExeHostEntryPointDescription : System.Fabric.Description.EntryPointDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExeHostEntryPointDescription extends System.Fabric.Description.EntryPointDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ExeHostEntryPointDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExeHostEntryPointDescription&#xA;Inherits EntryPointDescription" />
  <TypeSignature Language="F#" Value="type ExeHostEntryPointDescription = class&#xA;    inherit EntryPointDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.EntryPointDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>実行可能ファイルのエントリ ポイントに関する情報を提供します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public string Arguments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Arguments" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Arguments As String" />
      <MemberSignature Language="F#" Value="member this.Arguments : string" Usage="System.Fabric.Description.ExeHostEntryPointDescription.Arguments" />
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
          <para>取得または設定されたサービス マニフェストで指定されている実行可能ファイルに渡される引数。 </para>
        </summary>
        <value>
          <para>サービス マニフェストで指定されている実行可能ファイルに渡す引数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionEnabled">
      <MemberSignature Language="C#" Value="public bool ConsoleRedirectionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsoleRedirectionEnabled" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionEnabled : bool" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionEnabled" />
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
          <para>取得または設定を有効にするにまたは実行可能ファイル用のコンソールのリダイレクトを無効にするかどうかを示す値。 既定値は <languageKeyword>false</languageKeyword>です。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword> ; 実行可能ファイル用のコンソールのリダイレクトを有効にするそれ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionFileMaxSizeInKb">
      <MemberSignature Language="C#" Value="public long ConsoleRedirectionFileMaxSizeInKb { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConsoleRedirectionFileMaxSizeInKb" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileMaxSizeInKb" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionFileMaxSizeInKb As Long" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionFileMaxSizeInKb : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileMaxSizeInKb" />
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
          <para>取得またはコンソール リダイレクト ファイルの最大サイズを kb 単位で設定します。</para>
        </summary>
        <value>
          <para>コンソールのリダイレクトのファイルの最大サイズを (KB 単位)。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionFileRetentionCount">
      <MemberSignature Language="C#" Value="public long ConsoleRedirectionFileRetentionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConsoleRedirectionFileRetentionCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileRetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionFileRetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionFileRetentionCount : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileRetentionCount" />
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
          <para>取得または循環の方法でコンテンツを上書きする前に、コンソールのリダイレクトに使用されるファイルの最大数を設定します。 </para>
        </summary>
        <value>
          <para>循環の方法でコンテンツを上書きする前に、コンソールのリダイレクトに使用されるファイルの最大数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeriodicInterval">
      <MemberSignature Language="C#" Value="public long PeriodicInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PeriodicInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.PeriodicInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PeriodicInterval As Long" />
      <MemberSignature Language="F#" Value="member this.PeriodicInterval : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.PeriodicInterval" />
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
          <para>取得または実行可能ファイルが定期的にアクティブにする必要がある場合、期間を設定します。 </para>
        </summary>
        <value>
          <para>までの時間、実行可能ファイルは、定期的にアクティブにする必要があります。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Program">
      <MemberSignature Language="C#" Value="public string Program { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Program" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.Program" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Program As String" />
      <MemberSignature Language="F#" Value="member this.Program : string" Usage="System.Fabric.Description.ExeHostEntryPointDescription.Program" />
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
          <para>取得またはサービス マニフェストで指定されている実行可能ファイル名を設定します。</para>
        </summary>
        <value>
          <para>サービス マニフェストで指定されている実行可能ファイル名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ExeHostEntryPointDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="exeHostEntryPointDescription.ToString " />
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
          <para>このエントリ ポイントの文字列形式を取得します。</para>
        </summary>
        <returns>
          <para>このエントリ ポイントの文字列形式。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkingFolder">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ExeHostWorkingFolder WorkingFolder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ExeHostWorkingFolder WorkingFolder" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.WorkingFolder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkingFolder As ExeHostWorkingFolder" />
      <MemberSignature Language="F#" Value="member this.WorkingFolder : System.Fabric.Description.ExeHostWorkingFolder" Usage="System.Fabric.Description.ExeHostEntryPointDescription.WorkingFolder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostWorkingFolder</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはサービス マニフェストで指定されている実行可能ファイルの作業フォルダーを設定します。</para>
        </summary>
        <value>
          <para>サービス マニフェストで指定されている実行可能ファイルの作業フォルダーです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
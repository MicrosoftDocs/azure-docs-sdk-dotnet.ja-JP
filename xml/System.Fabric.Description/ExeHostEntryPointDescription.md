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
      <para><span data-ttu-id="290dc-101">実行可能ファイルのエントリ ポイントに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="290dc-101">Provides information about the executable entry point.</span></span></para>
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
          <para><span data-ttu-id="290dc-102">取得または設定されたサービス マニフェストで指定されている実行可能ファイルに渡される引数。</span><span class="sxs-lookup"><span data-stu-id="290dc-102">Gets or sets the arguments passed to the executable as specified in the service manifest.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="290dc-103">サービス マニフェストで指定されている実行可能ファイルに渡す引数。</span><span class="sxs-lookup"><span data-stu-id="290dc-103">The arguments passed to the executable as specified in the service manifest.</span></span></para>
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
          <para><span data-ttu-id="290dc-104">取得または設定を有効にするにまたは実行可能ファイル用のコンソールのリダイレクトを無効にするかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="290dc-104">Gets or sets a value that indicates whether to enable or disable console redirection for executables.</span></span> <span data-ttu-id="290dc-105">既定値は <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="290dc-105">Default is <languageKeyword>false</languageKeyword>.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="290dc-106"><languageKeyword>true</languageKeyword> ; 実行可能ファイル用のコンソールのリダイレクトを有効にするそれ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="290dc-106"><languageKeyword>true</languageKeyword> to enable console redirection for executables; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
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
          <para><span data-ttu-id="290dc-107">取得またはコンソール リダイレクト ファイルの最大サイズを kb 単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="290dc-107">Gets or sets the maximum size in KB for console redirection file.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="290dc-108">コンソールのリダイレクトのファイルの最大サイズを (KB 単位)。</span><span class="sxs-lookup"><span data-stu-id="290dc-108">The maximum size in KB for console redirection file.</span></span></para>
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
          <para><span data-ttu-id="290dc-109">取得または循環の方法でコンテンツを上書きする前に、コンソールのリダイレクトに使用されるファイルの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="290dc-109">Gets or sets the maximum number of files used for console redirection before overwriting content in circular way.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="290dc-110">循環の方法でコンテンツを上書きする前に、コンソールのリダイレクトに使用されるファイルの最大数。</span><span class="sxs-lookup"><span data-stu-id="290dc-110">The maximum number of files used for console redirection before overwriting content in circular way.</span></span></para>
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
          <para><span data-ttu-id="290dc-111">取得または実行可能ファイルが定期的にアクティブにする必要がある場合、期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="290dc-111">Gets or sets the time period, if executable needs to be activated periodically.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="290dc-112">までの時間、実行可能ファイルは、定期的にアクティブにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="290dc-112">The time period the executable needs to be activated periodically.</span></span></para>
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
          <para><span data-ttu-id="290dc-113">取得またはサービス マニフェストで指定されている実行可能ファイル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="290dc-113">Gets or sets the executable name as specified in the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="290dc-114">サービス マニフェストで指定されている実行可能ファイル名。</span><span class="sxs-lookup"><span data-stu-id="290dc-114">The executable name as specified in the service manifest.</span></span></para>
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
          <para><span data-ttu-id="290dc-115">このエントリ ポイントの文字列形式を取得します。</span><span class="sxs-lookup"><span data-stu-id="290dc-115">Gets the string representation of this entry point.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="290dc-116">このエントリ ポイントの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="290dc-116">The string representation of this entry point.</span></span></para>
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
          <para><span data-ttu-id="290dc-117">取得またはサービス マニフェストで指定されている実行可能ファイルの作業フォルダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="290dc-117">Gets or sets the working folder for the executable as specified in the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="290dc-118">サービス マニフェストで指定されている実行可能ファイルの作業フォルダーです。</span><span class="sxs-lookup"><span data-stu-id="290dc-118">The working folder for the executable as specified in the service manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
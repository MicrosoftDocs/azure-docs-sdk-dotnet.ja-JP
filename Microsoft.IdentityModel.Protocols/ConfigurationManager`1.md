<Type Name="ConfigurationManager&lt;T&gt;" FullName="Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class ConfigurationManager&lt;T&gt; : Microsoft.IdentityModel.Protocols.IConfigurationManager&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ConfigurationManager`1&lt;class T&gt; extends System.Object implements class Microsoft.IdentityModel.Protocols.IConfigurationManager`1&lt;!T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.ConfigurationManager`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ConfigurationManager(Of T)&#xA;Implements IConfigurationManager(Of T)" />
  <TypeSignature Language="F#" Value="type ConfigurationManager&lt;'T (requires 'T : null)&gt; = class&#xA;    interface IConfigurationManager&lt;'T (requires 'T : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Protocols.IConfigurationManager&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" /> の型。</typeparam>
    <summary>
            構成データの取得を管理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigurationManager (string metadataAddress, Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt; configRetriever);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadataAddress, class Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1&lt;!T&gt; configRetriever) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.#ctor(System.String,Microsoft.IdentityModel.Protocols.IConfigurationRetriever{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (metadataAddress As String, configRetriever As IConfigurationRetriever(Of T))" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt; : string * Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt; (metadataAddress, configRetriever)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadataAddress" Type="System.String" />
        <Parameter Name="configRetriever" Type="Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="metadataAddress">構成を取得するアドレス。</param>
        <param name="configRetriever"><see cref="T:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1" /></param>
        <summary>
            新しい Instantiaties<see cref="T:Microsoft.IdentityModel.Protocols.ConfigurationManager`1" />を自動管理し、構成データの更新を制御します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigurationManager (string metadataAddress, Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt; configRetriever, Microsoft.IdentityModel.Protocols.IDocumentRetriever docRetriever);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadataAddress, class Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1&lt;!T&gt; configRetriever, class Microsoft.IdentityModel.Protocols.IDocumentRetriever docRetriever) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.#ctor(System.String,Microsoft.IdentityModel.Protocols.IConfigurationRetriever{`0},Microsoft.IdentityModel.Protocols.IDocumentRetriever)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (metadataAddress As String, configRetriever As IConfigurationRetriever(Of T), docRetriever As IDocumentRetriever)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt; : string * Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;'T (requires 'T : null)&gt; * Microsoft.IdentityModel.Protocols.IDocumentRetriever -&gt; Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt; (metadataAddress, configRetriever, docRetriever)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadataAddress" Type="System.String" />
        <Parameter Name="configRetriever" Type="Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt;" />
        <Parameter Name="docRetriever" Type="Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
      </Parameters>
      <Docs>
        <param name="metadataAddress">構成を取得するアドレス。</param>
        <param name="configRetriever"><see cref="T:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1" /></param>
        <param name="docRetriever"><see cref="T:Microsoft.IdentityModel.Protocols.IDocumentRetriever" />をアクセスを実行する構成を取得します。</param>
        <summary>
            新しい Instantiaties<see cref="T:Microsoft.IdentityModel.Protocols.ConfigurationManager`1" />を自動管理し、構成データの更新を制御します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">'DocRetriever' が null の場合は。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigurationManager (string metadataAddress, Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt; configRetriever, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadataAddress, class Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1&lt;!T&gt; configRetriever, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.#ctor(System.String,Microsoft.IdentityModel.Protocols.IConfigurationRetriever{`0},System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt; : string * Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;'T (requires 'T : null)&gt; * System.Net.Http.HttpClient -&gt; Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt; (metadataAddress, configRetriever, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadataAddress" Type="System.String" />
        <Parameter Name="configRetriever" Type="Microsoft.IdentityModel.Protocols.IConfigurationRetriever&lt;T&gt;" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="metadataAddress">構成を取得するアドレス。</param>
        <param name="configRetriever"><see cref="T:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1" /></param>
        <param name="httpClient">構成を取得するときに使用するクライアント。</param>
        <summary>
            新しい Instantiaties<see cref="T:Microsoft.IdentityModel.Protocols.ConfigurationManager`1" />を自動管理し、構成データの更新を制御します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutomaticRefreshInterval">
      <MemberSignature Language="C#" Value="public TimeSpan AutomaticRefreshInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutomaticRefreshInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.AutomaticRefreshInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutomaticRefreshInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutomaticRefreshInterval : TimeSpan with get, set" Usage="Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;.AutomaticRefreshInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:System.TimeSpan" />自動メタデータ更新を実行する頻度を制御します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultAutomaticRefreshInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultAutomaticRefreshInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultAutomaticRefreshInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.DefaultAutomaticRefreshInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultAutomaticRefreshInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultAutomaticRefreshInterval : TimeSpan" Usage="Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;.DefaultAutomaticRefreshInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            1 日は既定の時間間隔、つまりその後、<see cref="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.GetConfigurationAsync" />新しい構成を取得します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRefreshInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultRefreshInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultRefreshInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.DefaultRefreshInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultRefreshInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultRefreshInterval : TimeSpan" Usage="Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;.DefaultRefreshInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            30 秒は、既定の時間間隔を渡す必要がありますを<see cref="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.RequestRefresh" />新しい構成を取得します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetConfigurationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetConfigurationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.GetConfigurationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationAsync () As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.GetConfigurationAsync : unit -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;" Usage="configurationManager.GetConfigurationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Protocols.ConfigurationManager`1/&lt;GetConfigurationAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            構成の更新バージョンを取得します。
            </summary>
        <returns>T 型の構成</returns>
        <remarks>最後の呼び出しからの経過時間の場合より小さい<see cref="P:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.AutomaticRefreshInterval" />し<see cref="M:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1.GetConfigurationAsync(System.String,Microsoft.IdentityModel.Protocols.IDocumentRetriever,System.Threading.CancellationToken)" />は呼び出されませんされ、現在の構成が返されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetConfigurationAsync (System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetConfigurationAsync(valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.GetConfigurationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationAsync (cancel As CancellationToken) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;&#xA;override this.GetConfigurationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;" Usage="configurationManager.GetConfigurationAsync cancel" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.GetConfigurationAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Protocols.ConfigurationManager`1/&lt;GetConfigurationAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancel">CancellationToken</param>
        <summary>
            構成の更新バージョンを取得します。
            </summary>
        <returns>T 型の構成</returns>
        <remarks>最後の呼び出しからの経過時間の場合より小さい<see cref="P:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.AutomaticRefreshInterval" />し<see cref="M:Microsoft.IdentityModel.Protocols.IConfigurationRetriever`1.GetConfigurationAsync(System.String,Microsoft.IdentityModel.Protocols.IDocumentRetriever,System.Threading.CancellationToken)" />は呼び出されませんされ、現在の構成が返されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumAutomaticRefreshInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MinimumAutomaticRefreshInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MinimumAutomaticRefreshInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.MinimumAutomaticRefreshInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MinimumAutomaticRefreshInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MinimumAutomaticRefreshInterval : TimeSpan" Usage="Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;.MinimumAutomaticRefreshInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            5 分間は、自動更新の最小値です。 <see cref="P:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.AutomaticRefreshInterval" />設定できませんこの値よりも小さいです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumRefreshInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MinimumRefreshInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MinimumRefreshInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.MinimumRefreshInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MinimumRefreshInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MinimumRefreshInterval : TimeSpan" Usage="Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;.MinimumRefreshInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            1 秒間は、最小の時間間隔を渡す必要がありますに<see cref="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.RequestRefresh" />新しい構成を取得します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshInterval">
      <MemberSignature Language="C#" Value="public TimeSpan RefreshInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RefreshInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.RefreshInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RefreshInterval : TimeSpan with get, set" Usage="Microsoft.IdentityModel.Protocols.ConfigurationManager&lt;'T (requires 'T : null)&gt;.RefreshInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得が失敗したか、更新が明示的に要求されたイベントの取得間隔の最小時間。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRefresh">
      <MemberSignature Language="C#" Value="public void RequestRefresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RequestRefresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.RequestRefresh" />
      <MemberSignature Language="VB.NET" Value="Public Sub RequestRefresh ()" />
      <MemberSignature Language="F#" Value="abstract member RequestRefresh : unit -&gt; unit&#xA;override this.RequestRefresh : unit -&gt; unit" Usage="configurationManager.RequestRefresh " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.RequestRefresh</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            要求をその次に呼び出した<see cref="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.GetConfigurationAsync" />新しい構成を取得します。
            <para>前回の更新がよりも大きかった場合<see cref="P:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.RefreshInterval" />を次に呼び出したし<see cref="M:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.GetConfigurationAsync" />新しい構成を取得します</para>。<para>場合<see cref="P:Microsoft.IdentityModel.Protocols.ConfigurationManager`1.RefreshInterval" />  ==  <see cref="F:System.TimeSpan.MaxValue" />このメソッドでは何も行われません。</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ApplicationDescription" FullName="System.Fabric.Description.ApplicationDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationDescription" />
  <TypeSignature Language="F#" Value="type ApplicationDescription = class" />
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
      <para>使用して作成するアプリケーションについて説明<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:System.Fabric.Description.ApplicationDescription" />クラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationDescription (Uri applicationName, string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationDescription.#ctor(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, applicationTypeName As String, applicationTypeVersion As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationDescription : Uri * string * string -&gt; System.Fabric.Description.ApplicationDescription" Usage="new System.Fabric.Description.ApplicationDescription (applicationName, applicationTypeName, applicationTypeVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <param name="applicationTypeName">
          <para>アプリケーションの種類の名前です。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーションの種類のバージョンです。</para>
        </param>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:System.Fabric.Description.ApplicationDescription" />アプリケーション インスタンス名、アプリケーションの種類名、およびアプリケーションの種類のバージョンを使用します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationDescription (Uri applicationName, string applicationTypeName, string applicationTypeVersion, System.Collections.Specialized.NameValueCollection applicationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string applicationTypeName, string applicationTypeVersion, class System.Collections.Specialized.NameValueCollection applicationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationDescription.#ctor(System.Uri,System.String,System.String,System.Collections.Specialized.NameValueCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, applicationTypeName As String, applicationTypeVersion As String, applicationParameters As NameValueCollection)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationDescription : Uri * string * string * System.Collections.Specialized.NameValueCollection -&gt; System.Fabric.Description.ApplicationDescription" Usage="new System.Fabric.Description.ApplicationDescription (applicationName, applicationTypeName, applicationTypeVersion, applicationParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="applicationParameters" Type="System.Collections.Specialized.NameValueCollection" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <param name="applicationTypeName">
          <para>アプリケーションの種類の名前です。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーションの種類のバージョンです。</para>
        </param>
        <param name="applicationParameters">
          <para>ApplicationManifest.xml で指定されているパラメーターの名前と値のペアのコレクションです。</para>
        </param>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:System.Fabric.Description.ApplicationDescription" />アプリケーション インスタンス名、アプリケーションの種類名、アプリケーション タイプのバージョン、およびアプリケーションのパラメーターのコレクションを使用します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはアプリケーション インスタンスの URI 名を設定します。</para>
        </summary>
        <value>
          <para>アプリケーション名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ApplicationParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationParameters As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ApplicationParameters : System.Collections.Specialized.NameValueCollection" Usage="System.Fabric.Description.ApplicationDescription.ApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ApplicationManifest.xml で指定されているパラメーターの名前と値のペアのコレクションを取得します。</para>
        </summary>
        <value>
          <para>ApplicationManifest.xml で指定されているパラメーターの名前と値のペアのコレクション。</para>
        </value>
        <remarks>
            パラメーターの値の許容最大長は、1024 * 1024 文字 (終端の null 文字を含む) です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string with get, set" Usage="System.Fabric.Description.ApplicationDescription.ApplicationTypeName" />
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
          <para>取得または Service Fabric アプリケーションの種類の名前を設定します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類名です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string with get, set" Usage="System.Fabric.Description.ApplicationDescription.ApplicationTypeVersion" />
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
          <para>取得またはアプリケーションの種類のバージョンを設定します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類のバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public long MaximumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : int64 with get, set" Usage="System.Fabric.Description.ApplicationDescription.MaximumNodes" />
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
            取得または、このアプリケーションをインスタンス化するノードの最大数を設定します。
            </summary>
        <value>
          <para>
            スパンするこのアプリケーションが許可されているノードの数。 既定値は 0 です。
            0 の場合、アプリケーションは任意の数のクラスター内のノードにまたがることができます。
            </para>
          <para>
            このパラメーターがより小さい場合<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />、<see cref="T:System.ArgumentException" />場合にスローされます<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" />と呼びます。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; Metrics;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Metrics As IList(Of ApplicationMetricDescription) " />
      <MemberSignature Language="F#" Value="val mutable Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" Usage="System.Fabric.Description.ApplicationDescription.Metrics" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーションの性能が定義されているメトリックのリストを設定します。
            </summary>
        <returns>
            アプリケーションの容量のメトリックを指定します。 使用して各メトリックの指定された容量<see cref="T:System.Fabric.Description.ApplicationMetricDescription" />です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public long MinimumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : int64 with get, set" Usage="System.Fabric.Description.ApplicationDescription.MinimumNodes" />
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
            取得または、Service Fabric がこのアプリケーションの容量を予約はノードの最小数を設定します。
            </summary>
        <value>
          <para>
            Service Fabric が、クラスター内のこのアプリケーションを配置する容量を予約、ノードの数。
            ある意味ではありませんこれらすべてのノード上のレプリカを保持するアプリケーションが保証されるに注意してください。
            </para>
          <para>
            このパラメーターが 0 に設定されている場合は、容量は予約されません。
            </para>
          <para>
            このパラメーターがより大きい場合<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />、<see cref="T:System.ArgumentException" />場合にスローされます<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" />と呼びます。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ApplicationUpdateDescription" FullName="System.Fabric.Description.ApplicationUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpdateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpdateDescription" />
  <TypeSignature Language="F#" Value="type ApplicationUpdateDescription = class" />
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
            使用して更新されるアプリケーション容量の更新について説明します<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">アプリケーション インスタンス名の URI。</param>
        <summary>
            <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> の新しいインスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName, bool removeApplicationCapacity, long minimumNodes, long maximumNodes, System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, bool removeApplicationCapacity, int64 minimumNodes, int64 maximumNodes, class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri,System.Boolean,System.Int64,System.Int64,System.Collections.Generic.IList{System.Fabric.Description.ApplicationMetricDescription})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, removeApplicationCapacity As Boolean, minimumNodes As Long, maximumNodes As Long, metrics As IList(Of ApplicationMetricDescription))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri * bool * int64 * int64 * System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription (applicationName, removeApplicationCapacity, minimumNodes, maximumNodes, metrics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="removeApplicationCapacity" Type="System.Boolean" />
        <Parameter Name="minimumNodes" Type="System.Int64" />
        <Parameter Name="maximumNodes" Type="System.Int64" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" />
      </Parameters>
      <Docs>
        <param name="applicationName">アプリケーション インスタンス名の URI。</param>
        <param name="removeApplicationCapacity">
            アプリケーションの性能を削除するかどうかを示します (を参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />)。
            </param>
        <param name="minimumNodes">
            ノードの最小数 (を参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />)。
            </param>
        <param name="maximumNodes">
            ノードの最大数 (を参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />)
            </param>
        <param name="metrics">
            アプリケーションの容量メトリック (を参照してください<see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />)
            </param>
        <summary>
            新しいインスタンスを作成<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />アプリケーション容量パラメーターを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
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
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaximumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このアプリケーションをインスタンス化するノードの最大数を設定します。
            </summary>
        <value>
          <para>
            スパンするこのアプリケーションが許可されているノードの数。 既定値は 0 です。
            ゼロになった場合は、クラスター内のノードの数にかかわらずアプリケーションを配置することができます。
            アプリケーションを更新するときにこのパラメーターが指定されていない場合は、ノードの最大数は変更されません。
            </para>
          <para>
            このパラメーターがより小さい場合<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />、<see cref="T:System.ArgumentException" />場合にスローされます<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" />と呼びます。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; Metrics;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Metrics As IList(Of ApplicationMetricDescription) " />
      <MemberSignature Language="F#" Value="val mutable Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" Usage="System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
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
            アプリケーションの容量のメトリックを指定します。 各メトリックを使用するための容量が指定された<see cref="T:System.Fabric.Description.ApplicationMetricDescription" />です。
            このパラメーターが設定されていない場合、アプリケーションの容量メトリックは変更されませんアプリケーションを更新する場合。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinimumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはノードの最小数を設定します。
            </summary>
        <value>
          <para>
            Service Fabric が、クラスター内のこのアプリケーションを配置する容量を予約、ノードの数。
            ある意味ではありませんこれらすべてのノード上のレプリカを保持するアプリケーションが保証されるに注意してください。
            </para>
          <para>
            このパラメーターが 0 に設定されている場合は、容量は予約されません。 アプリケーションを更新するときに、このパラメーターが設定されていない場合は、ノードの最小数は変更されません。
            </para>
          <para>
            このパラメーターがより大きい場合<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />両方のパラメーターが指定されている場合、<see cref="T:System.ArgumentException" />場合にスローされます<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" />と呼びます。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveApplicationCapacity">
      <MemberSignature Language="C#" Value="public bool RemoveApplicationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveApplicationCapacity As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveApplicationCapacity : bool with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
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
            取得または RemoveApplicationCapacity フラグを設定します。
            </summary>
        <value>
            このアプリケーションのアプリケーションの容量に関連するすべてのパラメーターをオフにするために使用します。
            その他のアプリケーションの性能パラメーターと共に、このパラメーターを指定することはできません。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
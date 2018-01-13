<Type Name="IReplicationLink" FullName="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink">
  <TypeSignature Language="C#" Value="public interface IReplicationLink : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IReplicationLink&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReplicationLink implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IReplicationLink&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReplicationLink&#xA;Implements IHasId, IHasInner(Of ReplicationLinkInner), IHasName, IHasResourceGroup, IRefreshable(Of IReplicationLink)" />
  <TypeSignature Language="F#" Value="type IReplicationLink = interface&#xA;    interface IRefreshable&lt;IReplicationLink&gt;&#xA;    interface IHasInner&lt;ReplicationLinkInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IReplicationLink&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure SQL レプリケーション リンクの変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このレプリケーションが所属する SQL データベースの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Delete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete ()" />
      <MemberSignature Language="F#" Value="abstract member Delete : unit -&gt; unit" Usage="iReplicationLink.Delete " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            レプリケーション リンクを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public void Failover ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Failover() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Failover" />
      <MemberSignature Language="VB.NET" Value="Public Sub Failover ()" />
      <MemberSignature Language="F#" Value="abstract member Failover : unit -&gt; unit" Usage="iReplicationLink.Failover " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure SQL データベース レプリケーション リンクでは失敗します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task FailoverAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FailoverAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.FailoverAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FailoverAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicationLink.FailoverAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Azure SQL データベース レプリケーション リンクでは失敗します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public void ForceFailoverAllowDataLoss ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ForceFailoverAllowDataLoss() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ForceFailoverAllowDataLoss" />
      <MemberSignature Language="VB.NET" Value="Public Sub ForceFailoverAllowDataLoss ()" />
      <MemberSignature Language="F#" Value="abstract member ForceFailoverAllowDataLoss : unit -&gt; unit" Usage="iReplicationLink.ForceFailoverAllowDataLoss " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            強制的にフェールオーバー、Azure SQL データベース レプリケーション リンク データの損失になる可能性があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ForceFailoverAllowDataLossAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ForceFailoverAllowDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ForceFailoverAllowDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ForceFailoverAllowDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicationLink.ForceFailoverAllowDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            強制的にフェールオーバー、Azure SQL データベース レプリケーション リンク データの損失になる可能性があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="PartnerDatabase">
      <MemberSignature Language="C#" Value="public string PartnerDatabase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerDatabase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerDatabase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerDatabase As String" />
      <MemberSignature Language="F#" Value="member this.PartnerDatabase : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerDatabase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースのパートナーの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerLocation">
      <MemberSignature Language="C#" Value="public string PartnerLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerLocation As String" />
      <MemberSignature Language="F#" Value="member this.PartnerLocation : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースのパートナーの Azure リージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole PartnerRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole PartnerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerRole As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.PartnerRole : Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンクでは、パートナー SQL データベースの役割を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServer">
      <MemberSignature Language="C#" Value="public string PartnerServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerServer As String" />
      <MemberSignature Language="F#" Value="member this.PartnerServer : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PartnerServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースのパートナーをホストする Azure の SQL Server の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public int PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Integer" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : int" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンクの完了のシード処理の割合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationState">
      <MemberSignature Language="C#" Value="public string ReplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ReplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationState : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.ReplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンクのレプリケーション状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole Role" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.Role : Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンクには、SQL データベースの役割を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.SqlServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このレプリケーションが所属する SQL Server の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IReplicationLink.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得の開始時刻、レプリケーション リンク (ISO8601 形式)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
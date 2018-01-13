<Type Name="ICodePackageActivationContext" FullName="System.Fabric.ICodePackageActivationContext">
  <TypeSignature Language="C#" Value="public interface ICodePackageActivationContext : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICodePackageActivationContext implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ICodePackageActivationContext" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICodePackageActivationContext&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ICodePackageActivationContext = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Service Fabric のアクティベーション コンテキストを表しますには、サービスがアクティブになります。
            </summary>
    <remarks>サービス マニフェストからの情報と作業のように、現在アクティブ化されたコード パッケージに関する情報を含むディレクトリ、コンテキスト id などです。</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public string ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : string" Usage="System.Fabric.ICodePackageActivationContext.ApplicationName" />
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
            アプリケーションの名前を取得します。
            </summary>
        <value>アプリケーションの名前です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.ICodePackageActivationContext.ApplicationTypeName" />
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
            アプリケーションの種類名を取得します。
            </summary>
        <value>アプリケーションの種類名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageAddedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.CodePackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Event CodePackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イベント発生時に新しい<see cref="T:System.Fabric.CodePackage" />サービス マニフェストに追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageModifiedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.CodePackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Event CodePackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            いつ発生するイベント、<see cref="T:System.Fabric.CodePackage" />サービスではマニフェストを変更します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.ICodePackageActivationContext.CodePackageName" />
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
            アクティブ化されてファブリック コード パッケージの名前を取得します。
            </summary>
        <value>ファブリックの名前には、コード パッケージがアクティブになります。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageRemovedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.CodePackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Event CodePackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            いつ発生するイベント、<see cref="T:System.Fabric.CodePackage" />サービス マニフェストから削除されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageVersion">
      <MemberSignature Language="C#" Value="public string CodePackageVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.CodePackageVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageVersion : string" Usage="System.Fabric.ICodePackageActivationContext.CodePackageVersion" />
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
            アクティブ化されてファブリック コード パッケージのバージョンを取得します。
            </summary>
        <value>ファブリックのバージョンでは、コード パッケージがアクティブになります。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageAddedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Event ConfigurationPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イベント発生時に新しい<see cref="T:System.Fabric.ConfigurationPackage" />サービス マニフェストに追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageModifiedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Event ConfigurationPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            いつ発生するイベント、<see cref="T:System.Fabric.ConfigurationPackage" />サービスではマニフェストを変更します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageRemovedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Event ConfigurationPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            いつ発生するイベント、<see cref="T:System.Fabric.ConfigurationPackage" />サービス マニフェストから削除されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContextId">
      <MemberSignature Language="C#" Value="public string ContextId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContextId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.ContextId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContextId As String" />
      <MemberSignature Language="F#" Value="member this.ContextId : string" Usage="System.Fabric.ICodePackageActivationContext.ContextId" />
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
            コンテキスト ID を取得します。
            </summary>
        <value>コンテキスト id です。</value>
        <remarks>コンテキスト id は、1 つのサービス マニフェスト内のすべてのコード パッケージに同じです。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageAddedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.DataPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Event DataPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イベント発生時に新しい<see cref="T:System.Fabric.DataPackage" />サービス マニフェストに追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageModifiedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.DataPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Event DataPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            いつ発生するイベント、<see cref="T:System.Fabric.DataPackage" />サービスではマニフェストを変更します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageRemovedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.DataPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Event DataPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            いつ発生するイベント、<see cref="T:System.Fabric.DataPackage" />サービス マニフェストから削除されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPrincipals">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetApplicationPrincipals" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationPrincipals () As ApplicationPrincipalsDescription" />
      <MemberSignature Language="F#" Value="abstract member GetApplicationPrincipals : unit -&gt; System.Fabric.Description.ApplicationPrincipalsDescription" Usage="iCodePackageActivationContext.GetApplicationPrincipals " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationPrincipalsDescription</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション マニフェストで定義されているプリンシパルを取得します。
            </summary>
        <returns>アプリケーション マニフェストで定義されているプリンシパル。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetCodePackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetCodePackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetCodePackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="iCodePackageActivationContext.GetCodePackageNames " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス マニフェスト内のコード パッケージ名の一覧を取得します。
            </summary>
        <returns>サービス マニフェスト内のコード パッケージ名の一覧です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.CodePackage GetCodePackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.CodePackage GetCodePackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetCodePackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageObject (packageName As String) As CodePackage" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageObject : string -&gt; System.Fabric.CodePackage" Usage="iCodePackageActivationContext.GetCodePackageObject packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">コード パッケージの名前。</param>
        <summary>
            返します、<see cref="T:System.Fabric.CodePackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。
            </summary>
        <returns><see cref="T:System.Fabric.CodePackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</returns>
        <remarks>パッケージが見つからない場合は、KeyNotFoundException 例外をスローします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetConfigurationPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetConfigurationPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="iCodePackageActivationContext.GetConfigurationPackageNames " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス マニフェストの構成パッケージ名の一覧を取得します。
            </summary>
        <returns>サービス マニフェスト内の構成パッケージ名の一覧です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.ConfigurationPackage GetConfigurationPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.ConfigurationPackage GetConfigurationPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageObject (packageName As String) As ConfigurationPackage" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageObject : string -&gt; System.Fabric.ConfigurationPackage" Usage="iCodePackageActivationContext.GetConfigurationPackageObject packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ConfigurationPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">構成パッケージの名前。</param>
        <summary>
            返します、<see cref="T:System.Fabric.ConfigurationPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。
            </summary>
        <returns><see cref="T:System.Fabric.ConfigurationPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</returns>
        <remarks>パッケージが見つからない場合は、KeyNotFoundException 例外をスローします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetDataPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetDataPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetDataPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="iCodePackageActivationContext.GetDataPackageNames " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス マニフェスト内のデータ パッケージ名の一覧を取得します。
            </summary>
        <returns>データの一覧には、サービス マニフェストの名前がパッケージ化します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.DataPackage GetDataPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.DataPackage GetDataPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetDataPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageObject (packageName As String) As DataPackage" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageObject : string -&gt; System.Fabric.DataPackage" Usage="iCodePackageActivationContext.GetDataPackageObject packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">データ パッケージの名前。</param>
        <summary>
            返します、<see cref="T:System.Fabric.DataPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。
            </summary>
        <returns><see cref="T:System.Fabric.DataPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</returns>
        <remarks>パッケージが見つからない場合は、KeyNotFoundException 例外をスローします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointResourceDescription GetEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.EndpointResourceDescription GetEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint (endpointName As String) As EndpointResourceDescription" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoint : string -&gt; System.Fabric.Description.EndpointResourceDescription" Usage="iCodePackageActivationContext.GetEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.EndpointResourceDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName">エンドポイントの名前。</param>
        <summary>
            サービス マニフェストから名前が指定されたエンドポイントのリソースを取得します。
            </summary>
        <returns>指定した名前のエンドポイント リソースです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoints () As KeyedCollection(Of String, EndpointResourceDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoints : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.EndpointResourceDescription&gt;" Usage="iCodePackageActivationContext.GetEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.EndpointResourceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス マニフェスト内のエンドポイントのリソースを取得します。
            </summary>
        <returns>サービス マニフェスト内のエンドポイント リソース。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceGroupTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupTypes () As KeyedCollection(Of String, ServiceGroupTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceGroupTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceGroupTypeDescription&gt;" Usage="iCodePackageActivationContext.GetServiceGroupTypes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ServiceGroupTypeDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス マニフェスト内のサービス グループの種類の一覧を取得します。
            </summary>
        <returns>サービス マニフェスト内のサービス グループの種類の一覧。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestName">
      <MemberSignature Language="C#" Value="public string GetServiceManifestName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestName() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestName () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestName : unit -&gt; string" Usage="iCodePackageActivationContext.GetServiceManifestName " />
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
            サービス マニフェストの名前を取得します。
            </summary>
        <returns>サービス マニフェストの名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string GetServiceManifestVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestVersion () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestVersion : unit -&gt; string" Usage="iCodePackageActivationContext.GetServiceManifestVersion " />
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
            サービス マニフェストのバージョンを取得します。
            </summary>
        <returns>サービス マニフェストのバージョン。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypes () As KeyedCollection(Of String, ServiceTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceTypeDescription&gt;" Usage="iCodePackageActivationContext.GetServiceTypes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ServiceTypeDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス マニフェスト内のサービスの種類の一覧を取得します。
            </summary>
        <returns>サービス マニフェスト内のサービス型の一覧。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogDirectory">
      <MemberSignature Language="C#" Value="public string LogDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.LogDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogDirectory As String" />
      <MemberSignature Language="F#" Value="member this.LogDirectory : string" Usage="System.Fabric.ICodePackageActivationContext.LogDirectory" />
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
            アプリケーションを使用してログ ディレクトリへのパスを取得します。
            </summary>
        <value>コード パッケージのログ ディレクトリへのパス。</value>
        <remarks>パラメーター名のログインに ClusterManifest の LogicalDirectories セクションし、返されるパスを指定した場合は、パラメーター値にシンボリック リンクです。
            ex: 場合<LogicalDirectory LogicalDirectoryName="Log" MappedTo="F:\Log" />が指定されている LogDirectory に返されるパスは F:\Log\NodeId\ApplicationType_ApplicationVersion へのシンボリック リンクになります</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iCodePackageActivationContext.ReportApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</param>
        <summary>
            現在のアプリケーションの正常性を報告します。 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iCodePackageActivationContext.ReportApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            現在のアプリケーションの正常性を報告します。 レポートを送信する方法を制御するオプションを指定します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo">ヘルス情報をレポートします。</param>
        <summary>
            現在展開済みのアプリケーションの正常性を報告します。 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            現在展開済みのアプリケーションの正常性を報告します。 レポートを送信する方法を制御するオプションを指定します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedServicePackageHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo">ヘルス情報をレポートします。</param>
        <summary>
            現在の展開済みサービス パッケージの正常性を報告します。 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedServicePackageHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            現在の展開済みサービス パッケージの正常性を報告します。 正常性ストアに、レポートを送信する方法を制御する送信オプションを指定します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempDirectory">
      <MemberSignature Language="C#" Value="public string TempDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TempDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.TempDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TempDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TempDirectory : string" Usage="System.Fabric.ICodePackageActivationContext.TempDirectory" />
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
            アプリケーションを使用して Temp ディレクトリへのパスを取得します。
            </summary>
        <value>コード パッケージの Temp ディレクトリへのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkDirectory">
      <MemberSignature Language="C#" Value="public string WorkDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.WorkDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkDirectory As String" />
      <MemberSignature Language="F#" Value="member this.WorkDirectory : string" Usage="System.Fabric.ICodePackageActivationContext.WorkDirectory" />
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
            アプリケーションを使用して作業ディレクトリへのパスを取得します。
            </summary>
        <value>コード パッケージの作業ディレクトリへのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
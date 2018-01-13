<Type Name="CodePackageActivationContext" FullName="System.Fabric.CodePackageActivationContext">
  <TypeSignature Language="C#" Value="public class CodePackageActivationContext : IDisposable, System.Fabric.ICodePackageActivationContext3" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CodePackageActivationContext extends System.Object implements class System.Fabric.ICodePackageActivationContext, class System.Fabric.ICodePackageActivationContext2, class System.Fabric.ICodePackageActivationContext3, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CodePackageActivationContext" />
  <TypeSignature Language="VB.NET" Value="Public Class CodePackageActivationContext&#xA;Implements ICodePackageActivationContext3, IDisposable" />
  <TypeSignature Language="F#" Value="type CodePackageActivationContext = class&#xA;    interface ICodePackageActivationContext3&#xA;    interface ICodePackageActivationContext2&#xA;    interface ICodePackageActivationContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.ICodePackageActivationContext3</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>Service Fabric アプリケーションの実行中のコード パッケージに関する情報を含む、アクティブ化を表します。</para>
      <para><see cref="M:System.Fabric.FabricRuntime.GetActivationContext" />と<see cref="M:System.Fabric.FabricRuntime.GetActivationContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />アクティベーション コンテキストのインスタンスを取得するメソッドを使用できます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public string ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : string" Usage="System.Fabric.CodePackageActivationContext.ApplicationName" />
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
          <para>アプリケーションの名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.CodePackageActivationContext.ApplicationTypeName" />
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
          <para>アプリケーションの種類の名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageAdded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageAdded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageAdded" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageAdded" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageAdded As EventHandler(Of PackageAddedEventArgs(Of CodePackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageAdded : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " Usage="member this.CodePackageAdded : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use CodePackageAddedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに新しいコード パッケージが追加されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageAddedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.CodePackageAddedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに新しいコード パッケージが追加されると、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageModified">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageModified;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageModified" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageModified" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageModified As EventHandler(Of PackageModifiedEventArgs(Of CodePackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageModified : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " Usage="member this.CodePackageModified : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use CodePackageModifiedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストで既存のコード パッケージが変更されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.CodePackageModifiedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageModifiedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.CodePackageModifiedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストで既存のコード パッケージが変更されたときに、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.CodePackageActivationContext.CodePackageName" />
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
          <para>アクティブ化されてファブリック コード パッケージの名前を取得します。</para>
        </summary>
        <value>
          <para>ファブリックの名前には、コード パッケージがアクティブになります。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageRemoved">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageRemoved;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageRemoved" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageRemoved" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageRemoved As EventHandler(Of PackageRemovedEventArgs(Of CodePackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageRemoved : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " Usage="member this.CodePackageRemoved : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use CodePackageRemovedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストからコード パッケージが削除されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.CodePackageRemovedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageRemovedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.CodePackageRemovedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストからコード パッケージが削除されたときに、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageVersion">
      <MemberSignature Language="C#" Value="public string CodePackageVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.CodePackageVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageVersion : string" Usage="System.Fabric.CodePackageActivationContext.CodePackageVersion" />
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
          <para>アクティブ化されてファブリック コード パッケージのバージョンを取得します。</para>
        </summary>
        <value>
          <para>ファブリックのバージョンでは、コード パッケージがアクティブになります。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageAdded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageAdded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageAdded" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAdded" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageAdded As EventHandler(Of PackageAddedEventArgs(Of ConfigurationPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageAdded : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " Usage="member this.ConfigurationPackageAdded : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ConfigurationPackageAddedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに新しい構成パッケージが追加されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageAddedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageAddedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに追加されると、新しい構成パッケージは、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageModified">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageModified;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageModified" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageModified" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageModified As EventHandler(Of PackageModifiedEventArgs(Of ConfigurationPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageModified : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " Usage="member this.ConfigurationPackageModified : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ConfigurationPackageModifiedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストで、構成パッケージが変更されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageModifiedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageModifiedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageModifiedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに、構成パッケージが変更されたときに、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageRemoved">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageRemoved;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageRemoved" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemoved" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageRemoved As EventHandler(Of PackageRemovedEventArgs(Of ConfigurationPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageRemoved : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " Usage="member this.ConfigurationPackageRemoved : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ConfigurationPackageRemovedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストから構成パッケージが削除されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemovedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageRemovedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageRemovedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストから削除されると、構成パッケージは、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContextId">
      <MemberSignature Language="C#" Value="public string ContextId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContextId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ContextId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContextId As String" />
      <MemberSignature Language="F#" Value="member this.ContextId : string" Usage="System.Fabric.CodePackageActivationContext.ContextId" />
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
          <para>アプリケーション パッケージ名を持つには、サービス パッケージ名が修飾を表す ID を取得します。</para>
        </summary>
        <value>
          <para>コンテキスト id。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageAdded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageAdded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageAdded" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageAdded" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageAdded As EventHandler(Of PackageAddedEventArgs(Of DataPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageAdded : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " Usage="member this.DataPackageAdded : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use DataPackageAddedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに、データ パッケージが追加されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageAddedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.DataPackageAddedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに追加されると、データ パッケージは、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageModified">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageModified;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageModified" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageModified" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageModified As EventHandler(Of PackageModifiedEventArgs(Of DataPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageModified : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " Usage="member this.DataPackageModified : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use DataPackageModifiedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストで、データ パッケージが変更されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.DataPackageModifiedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageModifiedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.DataPackageModifiedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストに、データ パッケージが変更されたときに、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageRemoved">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageRemoved;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageRemoved" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageRemoved" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageRemoved As EventHandler(Of PackageRemovedEventArgs(Of DataPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageRemoved : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " Usage="member this.DataPackageRemoved : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use DataPackageRemovedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストから、データ パッケージが削除されたときに発生します。
            </summary>
        <remarks>互換性のために残されています。 代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.DataPackageRemovedEvent" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageRemovedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.DataPackageRemovedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス マニフェストから、データ パッケージが削除されたときに、アプリケーションのアップグレード中に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="codePackageActivationContext.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            コード パッケージのアクティベーション コンテキストを破棄します。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~CodePackageActivationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="codePackageActivationContext.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            オブジェクトが破棄される前に、現在のオブジェクトによって保持されているアンマネージ リソースのクリーンアップ操作を実行します。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPrincipals">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetApplicationPrincipals" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationPrincipals () As ApplicationPrincipalsDescription" />
      <MemberSignature Language="F#" Value="abstract member GetApplicationPrincipals : unit -&gt; System.Fabric.Description.ApplicationPrincipalsDescription&#xA;override this.GetApplicationPrincipals : unit -&gt; System.Fabric.Description.ApplicationPrincipalsDescription" Usage="codePackageActivationContext.GetApplicationPrincipals " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetApplicationPrincipals</InterfaceMember>
      </Implements>
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
          <para>アプリケーション マニフェストで定義されているすべてのプリンシパルを取得します。</para>
        </summary>
        <returns>
          <para>アプリケーション マニフェストで定義されているプリンシパル。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackage">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.CodePackageDescription GetCodePackage (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Description.CodePackageDescription GetCodePackage(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetCodePackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackage (packageName As String) As CodePackageDescription" />
      <MemberSignature Language="F#" Value="member this.GetCodePackage : string -&gt; System.Fabric.Description.CodePackageDescription" Usage="codePackageActivationContext.GetCodePackage packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use GetCodePackageObject method.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.CodePackageDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para>検索するパッケージの名前</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.Description.CodePackageDescription" />名前のオブジェクト。</para>
          <para>このメソッドは、互換性のために残されています。 <see cref="M:System.Fabric.CodePackageActivationContext.GetCodePackageObject(System.String)" />を使用します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.Description.CodePackageDescription" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">サービス マニフェストに、packageName が見つかりませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetCodePackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetCodePackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetCodePackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;&#xA;override this.GetCodePackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="codePackageActivationContext.GetCodePackageNames " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetCodePackageNames</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェスト内のコード パッケージ名の一覧を取得します。</para>
        </summary>
        <returns>
          <para>サービス マニフェスト内のコード パッケージ名の一覧です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.CodePackage GetCodePackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.CodePackage GetCodePackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetCodePackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageObject (packageName As String) As CodePackage" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageObject : string -&gt; System.Fabric.CodePackage&#xA;override this.GetCodePackageObject : string -&gt; System.Fabric.CodePackage" Usage="codePackageActivationContext.GetCodePackageObject packageName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetCodePackageObject(System.String)</InterfaceMember>
      </Implements>
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
        <param name="packageName">
          <para>検索するパッケージの名前</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.CodePackage" />名前のオブジェクト。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.CodePackage" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">サービス マニフェストに、packageName が見つかりませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackage">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ConfigurationPackageDescription GetConfigurationPackage (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Description.ConfigurationPackageDescription GetConfigurationPackage(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackage (packageName As String) As ConfigurationPackageDescription" />
      <MemberSignature Language="F#" Value="member this.GetConfigurationPackage : string -&gt; System.Fabric.Description.ConfigurationPackageDescription" Usage="codePackageActivationContext.GetConfigurationPackage packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use GetConfigurationPackageObject method.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ConfigurationPackageDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para>検索するパッケージの名前</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.Description.ConfigurationPackageDescription" />名前のオブジェクト。</para>
          <para>このメソッドは、互換性のために残されています。 <see cref="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackageObject(System.String)" />を使用します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.Description.ConfigurationPackageDescription" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">サービス マニフェストに、packageName が見つかりませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetConfigurationPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetConfigurationPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;&#xA;override this.GetConfigurationPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="codePackageActivationContext.GetConfigurationPackageNames " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageNames</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェストの構成パッケージ名の一覧を取得します。</para>
        </summary>
        <returns>
          <para>サービス マニフェスト内の構成パッケージ名の一覧です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.ConfigurationPackage GetConfigurationPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.ConfigurationPackage GetConfigurationPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageObject (packageName As String) As ConfigurationPackage" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageObject : string -&gt; System.Fabric.ConfigurationPackage&#xA;override this.GetConfigurationPackageObject : string -&gt; System.Fabric.ConfigurationPackage" Usage="codePackageActivationContext.GetConfigurationPackageObject packageName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageObject(System.String)</InterfaceMember>
      </Implements>
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
        <param name="packageName">
          <para>検索するパッケージの名前</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.ConfigurationPackage" />名前のオブジェクト。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.ConfigurationPackage" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">サービス マニフェストに、packageName が見つかりませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackage">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.DataPackageDescription GetDataPackage (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Description.DataPackageDescription GetDataPackage(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDataPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackage (packageName As String) As DataPackageDescription" />
      <MemberSignature Language="F#" Value="member this.GetDataPackage : string -&gt; System.Fabric.Description.DataPackageDescription" Usage="codePackageActivationContext.GetDataPackage packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use GetDataPackageObject method.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.DataPackageDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para>検索するパッケージの名前</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.Description.DataPackageDescription" />名前。</para>
          <para>このメソッドは、互換性のために残されています。 <see cref="M:System.Fabric.CodePackageActivationContext.GetDataPackageObject(System.String)" />を使用します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.Description.DataPackageDescription" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">サービス マニフェストに、packageName が見つかりませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetDataPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetDataPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDataPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;&#xA;override this.GetDataPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="codePackageActivationContext.GetDataPackageNames " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetDataPackageNames</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェスト内のデータ パッケージ名の一覧を取得します。</para>
        </summary>
        <returns>
          <para>データの一覧には、サービス マニフェストの名前がパッケージ化します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.DataPackage GetDataPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.DataPackage GetDataPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDataPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageObject (packageName As String) As DataPackage" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageObject : string -&gt; System.Fabric.DataPackage&#xA;override this.GetDataPackageObject : string -&gt; System.Fabric.DataPackage" Usage="codePackageActivationContext.GetDataPackageObject packageName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetDataPackageObject(System.String)</InterfaceMember>
      </Implements>
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
        <param name="packageName">
          <para>検索するパッケージの名前</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.DataPackage" />名前のオブジェクト。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.DataPackage" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">サービス マニフェストに、packageName が見つかりませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetDirectory">
      <MemberSignature Language="C#" Value="public string GetDirectory (string logicalDirectoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetDirectory(string logicalDirectoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDirectory (logicalDirectoryName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetDirectory : string -&gt; string&#xA;override this.GetDirectory : string -&gt; string" Usage="codePackageActivationContext.GetDirectory logicalDirectoryName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext3.GetDirectory(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logicalDirectoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="logicalDirectoryName">To be added.</param>
        <summary>
            作業ディレクトリ内のディレクトリのディレクトリ パスを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointResourceDescription GetEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.EndpointResourceDescription GetEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint (endpointName As String) As EndpointResourceDescription" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoint : string -&gt; System.Fabric.Description.EndpointResourceDescription&#xA;override this.GetEndpoint : string -&gt; System.Fabric.Description.EndpointResourceDescription" Usage="codePackageActivationContext.GetEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetEndpoint(System.String)</InterfaceMember>
      </Implements>
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
        <param name="endpointName">
          <para>エンドポイントの名前。</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.Description.EndpointResourceDescription" />名前。</para>
        </summary>
        <returns>
          <para>指定した名前を持つエンドポイントの説明です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>endpointName が null または空</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>エンドポイントがサービス マニフェストに見つかりませんでした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoints () As KeyedCollection(Of String, EndpointResourceDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoints : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.EndpointResourceDescription&gt;&#xA;override this.GetEndpoints : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.EndpointResourceDescription&gt;" Usage="codePackageActivationContext.GetEndpoints " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetEndpoints</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェスト内のすべての終了ポイントを取得します。</para>
        </summary>
        <returns>
          <para>サービス マニフェストの終点。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceGroupTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupTypes () As KeyedCollection(Of String, ServiceGroupTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceGroupTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceGroupTypeDescription&gt;&#xA;override this.GetServiceGroupTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceGroupTypeDescription&gt;" Usage="codePackageActivationContext.GetServiceGroupTypes " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceGroupTypes</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェスト内のサービス グループの種類の一覧を取得します。</para>
        </summary>
        <returns>
          <para>サービス マニフェスト内のサービス グループの種類の一覧。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestName">
      <MemberSignature Language="C#" Value="public string GetServiceManifestName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestName() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestName () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestName : unit -&gt; string&#xA;override this.GetServiceManifestName : unit -&gt; string" Usage="codePackageActivationContext.GetServiceManifestName " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceManifestName</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェストの名前を取得します。</para>
        </summary>
        <returns>
          <para>サービス マニフェストの名前。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string GetServiceManifestVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestVersion () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestVersion : unit -&gt; string&#xA;override this.GetServiceManifestVersion : unit -&gt; string" Usage="codePackageActivationContext.GetServiceManifestVersion " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceManifestVersion</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェストのバージョンを取得します。</para>
        </summary>
        <returns>
          <para>サービス マニフェストのバージョン。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypes () As KeyedCollection(Of String, ServiceTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceTypeDescription&gt;&#xA;override this.GetServiceTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceTypeDescription&gt;" Usage="codePackageActivationContext.GetServiceTypes " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceTypes</InterfaceMember>
      </Implements>
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
          <para>サービス マニフェスト内のサービスの種類の一覧を取得します。</para>
        </summary>
        <returns>
          <para>サービスの種類の一覧。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogDirectory">
      <MemberSignature Language="C#" Value="public string LogDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.LogDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogDirectory As String" />
      <MemberSignature Language="F#" Value="member this.LogDirectory : string" Usage="System.Fabric.CodePackageActivationContext.LogDirectory" />
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
          <para>アプリケーションを使用してログ ディレクトリへのパスを取得します。</para>
        </summary>
        <value>
          <para>アプリケーションへのパスは、ディレクトリを記録します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit&#xA;override this.ReportApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="codePackageActivationContext.ReportApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <summary>
            現在のアプリケーションの正常性を報告します。 
            </summary>
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.CodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit&#xA;override this.ReportApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="codePackageActivationContext.ReportApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            現在のアプリケーションの正常性を報告します。
            レポートを送信する方法を制御するオプションを指定します。
            </summary>
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit&#xA;override this.ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="codePackageActivationContext.ReportDeployedApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <summary>
            現在展開済みのアプリケーションの正常性を報告します。 
            </summary>
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.CodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit&#xA;override this.ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="codePackageActivationContext.ReportDeployedApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            現在展開済みのアプリケーションの正常性を報告します。 
            </summary>
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation -&gt; unit&#xA;override this.ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="codePackageActivationContext.ReportDeployedServicePackageHealth healthInfo" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <summary>
            現在の展開済みサービス パッケージの正常性を報告します。 
            </summary>
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.CodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit&#xA;override this.ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="codePackageActivationContext.ReportDeployedServicePackageHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            現在の展開済みサービス パッケージの正常性を報告します。 
            </summary>
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceListenAddress">
      <MemberSignature Language="C#" Value="public string ServiceListenAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServiceListenAddress : string" Usage="System.Fabric.CodePackageActivationContext.ServiceListenAddress" />
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
          <para>これで、サービスが通信リスナーを開始します。 アドレスです。</para>
        </summary>
        <value>
          <para>これで、サービスが通信リスナーを開始します。 アドレスです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePublishAddress">
      <MemberSignature Language="C#" Value="public string ServicePublishAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServicePublishAddress : string" Usage="System.Fabric.CodePackageActivationContext.ServicePublishAddress" />
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
          <para>リッスン アドレスとして、サービスが公開されるアドレスです。</para>
        </summary>
        <value>
          <para>リッスン アドレスとして、サービスが公開されるアドレスです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempDirectory">
      <MemberSignature Language="C#" Value="public string TempDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TempDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.TempDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TempDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TempDirectory : string" Usage="System.Fabric.CodePackageActivationContext.TempDirectory" />
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
          <para>アプリケーションがの一時ファイルを Temp ディレクトリへのパスを取得します。</para>
        </summary>
        <value>
          <para>Temp ディレクトリへのパス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkDirectory">
      <MemberSignature Language="C#" Value="public string WorkDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.WorkDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkDirectory As String" />
      <MemberSignature Language="F#" Value="member this.WorkDirectory : string" Usage="System.Fabric.CodePackageActivationContext.WorkDirectory" />
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
          <para>アプリケーションがデータの格納に使用できる作業ディレクトリへのパスを取得します。 例: レプリカの状態。</para>
        </summary>
        <value>
          <para>作業ディレクトリへのパス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
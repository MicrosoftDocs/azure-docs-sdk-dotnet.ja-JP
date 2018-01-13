<Type Name="ICodePackageActivationContext2" FullName="System.Fabric.ICodePackageActivationContext2">
  <TypeSignature Language="C#" Value="public interface ICodePackageActivationContext2 : IDisposable, System.Fabric.ICodePackageActivationContext" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICodePackageActivationContext2 implements class System.Fabric.ICodePackageActivationContext, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ICodePackageActivationContext2" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICodePackageActivationContext2&#xA;Implements ICodePackageActivationContext, IDisposable" />
  <TypeSignature Language="F#" Value="type ICodePackageActivationContext2 = interface&#xA;    interface ICodePackageActivationContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.ICodePackageActivationContext</InterfaceName>
    </Interface>
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
    <Member MemberName="ServiceListenAddress">
      <MemberSignature Language="C#" Value="public string ServiceListenAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext2.ServiceListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServiceListenAddress : string" Usage="System.Fabric.ICodePackageActivationContext2.ServiceListenAddress" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext2.ServicePublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServicePublishAddress : string" Usage="System.Fabric.ICodePackageActivationContext2.ServicePublishAddress" />
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
  </Members>
</Type>
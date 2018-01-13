<Type Name="ServiceFromTemplateDescription" FullName="System.Fabric.Description.ServiceFromTemplateDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceFromTemplateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceFromTemplateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceFromTemplateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceFromTemplateDescription" />
  <TypeSignature Language="F#" Value="type ServiceFromTemplateDescription = class" />
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
            現在のアプリケーション マニフェストであらかじめ定義されているサービス テンプレートから作成される Service Fabric サービスについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceFromTemplateDescription (Uri applicationName, Uri serviceName, string serviceDnsName, string serviceTypeName, System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, class System.Uri serviceName, string serviceDnsName, string serviceTypeName, valuetype System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceFromTemplateDescription.#ctor(System.Uri,System.Uri,System.String,System.String,System.Fabric.Description.ServicePackageActivationMode,System.Byte[])" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceFromTemplateDescription : Uri * Uri * string * string * System.Fabric.Description.ServicePackageActivationMode * byte[] -&gt; System.Fabric.Description.ServiceFromTemplateDescription" Usage="new System.Fabric.Description.ServiceFromTemplateDescription (applicationName, serviceName, serviceDnsName, serviceTypeName, servicePackageActivationMode, initializationData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceDnsName" Type="System.String" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="servicePackageActivationMode" Type="System.Fabric.Description.ServicePackageActivationMode" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName">サービスが作成されるアプリケーションのサービス ファブリック名。</param>
        <param name="serviceName">作成するサービスの名前です。</param>
        <param name="serviceDnsName">作成するサービスの DNS 名。</param>
        <param name="serviceTypeName">ServiceType の名前です。 サービス マニフェストで指定された ServiceTypeName と同じにする必要があります。</param>
        <param name="servicePackageActivationMode">
          <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成を使用します。
            </param>
        <param name="initializationData">サービスに渡される初期化データ。</param>
        <summary>
            インスタンスを作成<see cref="T:System.Fabric.Description.ServiceFromTemplateDescription" />指定パラメーターを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ApplicationName" />
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
            サービスが作成されるアプリケーションのサービス ファブリック名。
            </summary>
        <value>
            返します<see cref="T:System.Uri" />Service Fabric アプリケーションの名前を表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.Description.ServiceFromTemplateDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または作成されるときに、サービス グループのインスタンスまたはレプリカへ渡される初期化データを設定します。
            </summary>
        <value>
          <para><see cref="T:System.Byte" /> の配列を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDnsName">
      <MemberSignature Language="C#" Value="public string ServiceDnsName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceDnsName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceDnsName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceDnsName : string" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceDnsName" />
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
            作成するサービスの DNS 名。
            </summary>
        <value>
            返します<see cref="T:System.String" />Service Fabric サービスの DNS 名を表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceName" />
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
            作成するサービスの名前です。
            </summary>
        <value>
            返します<see cref="T:System.Uri" />Service Fabric サービスの名前を表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServicePackageActivationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービス。
            </summary>
        <value>
             <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> 列挙型。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceTypeName" />
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
            作成するサービスの種類の名前です。
            </summary>
        <value>
            返します<see cref="T:System.String" />Service Fabric サービスの型名を表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
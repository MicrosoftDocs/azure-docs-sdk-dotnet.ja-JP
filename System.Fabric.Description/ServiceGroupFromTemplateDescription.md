<Type Name="ServiceGroupFromTemplateDescription" FullName="System.Fabric.Description.ServiceGroupFromTemplateDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupFromTemplateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupFromTemplateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceGroupFromTemplateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupFromTemplateDescription" />
  <TypeSignature Language="F#" Value="type ServiceGroupFromTemplateDescription = class" />
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
            現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートから作成するサービス グループについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupFromTemplateDescription (Uri applicationName, Uri serviceName, string serviceTypeName, System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, valuetype System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupFromTemplateDescription.#ctor(System.Uri,System.Uri,System.String,System.Fabric.Description.ServicePackageActivationMode,System.Byte[])" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceGroupFromTemplateDescription : Uri * Uri * string * System.Fabric.Description.ServicePackageActivationMode * byte[] -&gt; System.Fabric.Description.ServiceGroupFromTemplateDescription" Usage="new System.Fabric.Description.ServiceGroupFromTemplateDescription (applicationName, serviceName, serviceTypeName, servicePackageActivationMode, initializationData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="servicePackageActivationMode" Type="System.Fabric.Description.ServicePackageActivationMode" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName">サービス グループのアプリケーションの名前です。</param>
        <param name="serviceName">&gt;サービス グループのサービス名です。</param>
        <param name="serviceTypeName">サービス グループのサービスの種類名です。</param>
        <param name="servicePackageActivationMode">
          <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービス グループの作成に使用します。
            </param>
        <param name="initializationData">サービスのグループに渡される初期化データ。</param>
        <summary>
            インスタンスを作成<see cref="T:System.Fabric.Description.ServiceGroupFromTemplateDescription" />指定パラメーターを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ApplicationName" />
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
            グループが所属するどのサービス アプリケーションの名前。
            </summary>
        <value>
            <see cref="T:System.Uri" /> Service Fabric アプリケーションの名前を表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.InitializationData" />
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
          <para> 取得または作成するときは、渡される初期化データをサービス インスタンスまたはレプリカに設定します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Byte" /> の配列を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceName" />
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
            グループの名前、サービスを作成します。
            </summary>
        <value>
            <see cref="T:System.Uri" /> Service Fabric サービスのグループ名を表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ServicePackageActivationMode" />
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
            取得または設定、<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービス グループのです。
            </summary>
        <value>
            A<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />列挙します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceTypeName" />
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
            作成するサービスの名前です。
            </summary>
        <value>
            <see cref="T:System.String" /> Service Fabric サービスの型名を表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
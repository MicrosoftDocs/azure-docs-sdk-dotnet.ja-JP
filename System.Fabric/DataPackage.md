<Type Name="DataPackage" FullName="System.Fabric.DataPackage">
  <TypeSignature Language="C#" Value="public sealed class DataPackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataPackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DataPackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataPackage" />
  <TypeSignature Language="F#" Value="type DataPackage = class" />
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
      <para>このクラスは、アプリケーションにデータのパッケージを表します。 静的なデータの (アップグレードすることができます)。 アプリケーションによって使用される、データ パッケージで構成されます。 詳細については、https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model を参照してください。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.DataPackageDescription Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.DataPackageDescription Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As DataPackageDescription" />
      <MemberSignature Language="F#" Value="member this.Description : System.Fabric.Description.DataPackageDescription" Usage="System.Fabric.DataPackage.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.DataPackageDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="T:System.Fabric.Description.PackageDescription" />オブジェクトに関連付けられている、<see cref="T:System.Fabric.DataPackage" />です。 パッケージの説明は、名など、このパッケージに関する追加情報にアクセスするために使用できますのバージョンなどです。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Description.PackageDescription" /> に関連付けられている <see cref="T:System.Fabric.DataPackage" /> オブジェクト。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="System.Fabric.DataPackage.Path" />
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
          <para>ローカル パスを取得<see cref="T:System.Fabric.DataPackage" />です。 このパスには、データ パッケージの内容が含まれています。</para>
        </summary>
        <value>
          <para>ローカル パス<see cref="T:System.Fabric.DataPackage" />です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
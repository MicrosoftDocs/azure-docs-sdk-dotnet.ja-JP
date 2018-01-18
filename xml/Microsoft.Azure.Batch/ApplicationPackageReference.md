<Type Name="ApplicationPackageReference" FullName="Microsoft.Azure.Batch.ApplicationPackageReference">
  <TypeSignature Language="C#" Value="public class ApplicationPackageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ApplicationPackageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackageReference" />
  <TypeSignature Language="F#" Value="type ApplicationPackageReference = class&#xA;    interface ITransportObjectProvider&lt;ApplicationPackageReference&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="036bd-101">コンピューティング ノードを展開するアプリケーション パッケージへの参照。</span><span class="sxs-lookup"><span data-stu-id="036bd-101">A reference to an application package to be deployed to compute nodes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ApplicationPackageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="036bd-102"><see cref="T:Microsoft.Azure.Batch.ApplicationPackageReference" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="036bd-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ApplicationPackageReference" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationId">
      <MemberSignature Language="C#" Value="public string ApplicationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ApplicationPackageReference.ApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationId As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationId : string with get, set" Usage="Microsoft.Azure.Batch.ApplicationPackageReference.ApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="036bd-103">取得または計算ノードを展開するアプリケーションの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="036bd-103">Gets or sets the id of the application to be deployed on compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ApplicationPackageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Batch.ApplicationPackageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="036bd-104">取得または計算ノードを展開するアプリケーションのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="036bd-104">Gets or sets the version of the application to be deployed on compute nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="036bd-105">指定しない場合、既定のバージョンのアプリケーション、アプリケーションの設定で定義されているは展開されます。</span><span class="sxs-lookup"><span data-stu-id="036bd-105">If not specified, the default version of the application, as defined in the application settings, is deployed.</span></span> <span data-ttu-id="036bd-106">アプリケーション設定に既定のバージョンが定義されていない場合は、バージョンを指定する必要があります、<see cref="T:Microsoft.Azure.Batch.ApplicationPackageReference" />です。</span><span class="sxs-lookup"><span data-stu-id="036bd-106">If no default version is defined in the application settings, you must specify a version in the <see cref="T:Microsoft.Azure.Batch.ApplicationPackageReference" />.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
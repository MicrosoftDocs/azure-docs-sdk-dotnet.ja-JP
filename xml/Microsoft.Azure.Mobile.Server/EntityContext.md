<Type Name="EntityContext" FullName="Microsoft.Azure.Mobile.Server.EntityContext">
  <TypeSignature Language="C#" Value="public abstract class EntityContext : System.Data.Entity.DbContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityContext extends System.Data.Entity.DbContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.EntityContext" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityContext&#xA;Inherits DbContext" />
  <TypeSignature Language="F#" Value="type EntityContext = class&#xA;    inherit DbContext" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Data.Entity.DbContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ba8de-101"><see cref="T:Microsoft.Azure.Mobile.Server.EntityContext" />と同じ機能を提供する抽象基本クラスには、 <see cref="T:System.Data.Entity.DbContext" /> Visual Studio がスキャフォールディングされました。</span><span class="sxs-lookup"><span data-stu-id="ba8de-101">The <see cref="T:Microsoft.Azure.Mobile.Server.EntityContext" /> is an abstract base class which provides the same functionality as the <see cref="T:System.Data.Entity.DbContext" /> scaffolded by Visual Studio.</span></span> <span data-ttu-id="ba8de-102">使用する場合は、スキャフォールディング コードの代わりにこの基本クラスを使用することはオプション、<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />です。</span><span class="sxs-lookup"><span data-stu-id="ba8de-102">It is optional to use this base class instead of the scaffolded code when using a <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected EntityContext ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.EntityContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba8de-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.EntityContext" />既定のスキーマ名、サービス名から派生します。</span><span class="sxs-lookup"><span data-stu-id="ba8de-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.EntityContext" /> with the default schema name derived from the service name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnModelCreating">
      <MemberSignature Language="C#" Value="protected override void OnModelCreating (System.Data.Entity.DbModelBuilder modelBuilder);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnModelCreating(class System.Data.Entity.DbModelBuilder modelBuilder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.EntityContext.OnModelCreating(System.Data.Entity.DbModelBuilder)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnModelCreating (modelBuilder As DbModelBuilder)" />
      <MemberSignature Language="F#" Value="override this.OnModelCreating : System.Data.Entity.DbModelBuilder -&gt; unit" Usage="entityContext.OnModelCreating modelBuilder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="modelBuilder" Type="System.Data.Entity.DbModelBuilder" />
      </Parameters>
      <Docs>
        <param name="modelBuilder">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>